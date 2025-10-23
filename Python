# My-first-project
creating my first project using github
# We'll create a minimal NFT farm game project structure with a Hardhat smart-contract workspace
# and a lightweight React + Vite frontend scaffold wired to interact with the contract via ethers.js.
# Then we'll zip everything so the user can download and push to GitHub.
import os, json, textwrap, pathlib, zipfile

root = "/mnt/data/nft-farm-basic"
contracts_dir = os.path.join(root, "smart-contract", "contracts")
scripts_dir = os.path.join(root, "smart-contract", "scripts")
test_dir = os.path.join(root, "smart-contract", "test")
sc_dir = os.path.join(root, "smart-contract")
frontend_dir = os.path.join(root, "webapp")
frontend_src = os.path.join(frontend_dir, "src")
frontend_public = os.path.join(frontend_dir, "public")
frontend_components = os.path.join(frontend_src, "components")
frontend_abi = os.path.join(frontend_src, "abi")

# Create directories
for d in [contracts_dir, scripts_dir, test_dir, frontend_dir, frontend_src, frontend_public, frontend_components, frontend_abi]:
    os.makedirs(d, exist_ok=True)

# --- Root README ---
readme = """# NFT Farm Basic

Um projeto base de **jogo de fazenda NFT** composto por:

- **smart-contract (Hardhat + Solidity)**: contrato ERC-721 `FarmNFT` com grade de plantações on-chain (plant/harvest).
- **webapp (Vite + React + Ethers)**: front‑end simples para conectar a carteira, fazer *mint* do NFT de fazenda e plantar/colher.

> Ideal para você iniciar um repositório no GitHub e evoluir para um jogo completo (economia de tokens, itens, marketplace, etc.).

## 🚀 Estrutura

