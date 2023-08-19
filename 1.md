#!/bin/bash

SERVICE="192.168.0.118"
PING_COUNT=4

if [ $? -eq 0 ]; then
    echo "Сервис доступен."
else
    echo "Сервис недоступен."
fi
