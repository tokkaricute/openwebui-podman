# OpenWebUI Containerfile
# podman build -t open-webui-custom -f Containerfile 

# image
FROM ghcr.io/open-webui/open-webui:main

# Port
EXPOSE 8080

# Data
VOLUME /app/backend/data

# Env Var
ENV OLLAMA_BASE_URL=http://host.containers.internal:11434

# command at start
CMD ["bash", "start.sh"]
