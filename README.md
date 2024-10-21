# GenAI-On-Prem
A handy GoTo guide to deploy your own Generative AI on docker

## Deploy pre-configured model on Docker

- Clone Docker GenAI repo
```bash
git clone https://github.com/docker/genai-stack
```
- Create `.env` file from `.env.example` and make changes accordingly.
- Deploy model
```bash
docker compose up -d
```