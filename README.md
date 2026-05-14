# RobloxMem

## Paper

This project is based on our accepted paper:

**Memory Management of LLM-Driven Storytelling for AI-Native Narrative Games**

📄 [Read the paper](docs/TAAI2025_Paper.pdf)

## Demo Video

🎬 [Watch the demo video](https://www.youtube.com/watch?v=uZm0jRymoGM)

## Repository Structure

```text
.
├── server.py                  # Main backend server for LLM and memory interaction
├── uploadNPC.py               # Uploads NPC memory data
├── queryNPC.py                # Queries stored NPC memory
├── monitorMem.py              # Monitors memory records
├── deleteMem.py               # Deletes memory entries
├── npc_memory_dataset.json    # Example NPC memory dataset
├── instruction.md             # Prompt and system instruction design
├── requirements.txt           # Python dependencies
├── Dockerfile.server          # Docker configuration for the backend server
├── docker-compose.yml         # Docker Compose setup
├── docs/                      # Paper and supplementary materials
└── 流程圖.JPG        # System architecture diagram
