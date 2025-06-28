# ⚽ Football Player Re-identification

This project aims to detect and consistently re-identify football players across video frames using computer vision techniques. The core logic is implemented in the Jupyter notebook: `football-stealth.ipynb`.

The system attempts to track players across multiple frames by assigning consistent IDs, even as they move or change direction, using a combination of detection and tracking logic.

---

## 🛠️ Setup Instructions

### 📥 1. Clone the Repository or Download the ZIP

# ✅ Clone the repository
git clone https://github.com/kabir-999/football_player_identification.git
cd football_player_identification

# ✅ Create and activate a virtual environment
# For macOS/Linux:
python3 -m venv venv && source venv/bin/activate

# For Windows (run this in Command Prompt or PowerShell):
# python -m venv venv && venv\Scripts\activate

# ✅ Install all dependencies
pip install torch torchvision opencv-python numpy matplotlib
