# IMPORTANTE VEJA OS ARQUIVOS DE EXEMPLO

## Criar aquivo para seu dominio
sudo cp /etc/bind/db.local /etc/bind/romenson.local

## Adicionar o seu arquivo de dominio como uma zona DNS
sudo vim  named.conf.default-zones

## Adicionar recursividade ao DNS
sudo vim  named.conf.options
