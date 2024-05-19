# Filebeat Setup

## Voraussetzungen
- Docker
- Docker Compose

## Setup-Anweisungen

1. Klone das Repository:
   git clone https://github.com/alesearm/dockercompose 
   cd elasticstack

2. Compose erstellen
   docker-compose -f elastic-compose.yml up -d 

elasticstack/
├── README.md
├── elastic-compose.yml
└── filebeat
    ├── apache.log
    └── filebeat.yml

1 directory, 4 files
