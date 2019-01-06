# Mincraft bedrock-server
Updated Minecraft-Bedrock Project in Unraid Docker

    docker run -d --name=minecraft\
        -v '/bedrock-server/worlds:/minecraft/worlds'\
        -v '/bedrock-server/server.properties:/minecraft/server.properties'\
        --network host\
        --restart=always\
        ahiss/bedrock-server

Reference nguyer for the original docker container.
ath