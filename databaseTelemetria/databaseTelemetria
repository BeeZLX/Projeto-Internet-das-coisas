-- Criação do Banco de Dados
CREATE DATABASE telemetria_energia;

-- Tabela de Dispositivos (Medidores)
CREATE TABLE medidores (
    id SERIAL PRIMARY KEY,
    codigo_patrimonio VARCHAR(50) UNIQUE NOT NULL,
    localizacao VARCHAR(100),
    data_instalacao DATE DEFAULT CURRENT_DATE
);

-- Tabela de Leituras (Onde os dados chegam em tempo real)
CREATE TABLE leituras (
    id SERIAL PRIMARY KEY,
    id_medidor INTEGER REFERENCES medidores(id),
    tensao_v FLOAT NOT NULL,           -- Volts
    corrente_a FLOAT NOT NULL,         -- Amperes
    potencia_kw FLOAT NOT NULL,        -- Quilowatts
    temperatura_painel FLOAT,          -- Para monitorar pontos quentes (NR-10)
    data_hora TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
