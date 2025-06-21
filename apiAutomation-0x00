#!/bin/bash
url="https://pokeapi.co/api/v2/pokemon/pikachu"
output="data.json"
error_log="errors.txt"

curl -s -f "$url" -o "$output" || echo "Failed to fetch data for Pikachu" >> "$error_log"
