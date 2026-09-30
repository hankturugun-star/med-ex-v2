# Med-Ex v2

Medical visual question answering with visual grounding: upload a radiology image, ask a question, get an answer and a heatmap of the regions that drove it.

**Status:** in progress — data exploration (step 1 of 8)

## Plan
1. Data: SLAKE (primary), VQA-RAD, IU X-Ray
2. Zero-shot baseline: Qwen3-VL-2B-Instruct
3. LoRA fine-tune
4. Grounding eval (Grad-CAM vs. SLAKE organ masks)
5. Evaluation + failure analysis
6. FastAPI backend
7. Next.js + TypeScript frontend
8. Deploy (HF Spaces + Vercel/Cloudflare Pages)

## Data
SLAKE (Liu et al., ISBI 2021) — CC BY / CC BY-SA 4.0. Not redistributed here; downloaded at runtime.

> Not for clinical use.
