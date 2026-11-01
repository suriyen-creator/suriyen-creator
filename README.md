<div align="right">
  <img src="https://komarev.com/ghpvc/?username=suriyen-creator&color=27c93f&style=flat-square&label=VISITOR_COUNT" alt="Visitor Count" />
</div>

```bash
suriyen@workstation:~$ fortune -s philosophy
```
> *"I like building things that don't stop at the screen. If software doesn't touch the physical world, it remains just an abstraction."*

```bash
suriyen@workstation:~$ fastfetch --profile
```

```text
   _____ _    _ _____  _______     ________ _   _ 
  / ____| |  | |  __ \|_   _\ \   / /  ____| \ | |
 | (___ | |  | | |__) | | |  \ \_/ /| |__  |  \| |
  \___ \| |  | |  _  /  | |   \   / |  __| | . ` |
  ____) | |__| | | \ \ _| |_   | |  | |____| |\  |
 |_____/ \____/|_|  \_\_____|  |_|  |______|_| \_|
```

```yaml
Developer:    SURIYEN (6e5tz)
Role:         AI / Machine Learning & Robotics Developer
Hardware:     Dobot Magician (4-DOF Arm) · Hikrobot Industrial Camera (MVS SDK)
Perception:   YOLOv8 · Faster-Whisper (Offline CPU INT8) · OpenCV · Scikit-Learn · Gemini API
Stack:        Python · PowerShell · Streamlit · NumPy · Windows Rice
Personal Web: https://6e5tz.runs-on.dev
```

---

### 📡 Active Hardware & Vision Pipelines

```bash
suriyen@workstation:~$ ./inspect_hardware_pipelines.sh --verbose
```

* **[SYS_01] Glass Defect Sorting System** — [`suriyen-creator/glass-defect-sorting-system`](https://github.com/suriyen-creator/glass-defect-sorting-system)
  ```text
  [Hikrobot MVS GigE] ──> [NumPy Frame Buffer] ──> [YOLOv8 Broken/NonBroken] ──> [Validation Gate] ──> [Dobot Suction Sort]
  ```
  *Solo vision-to-robot industrial pipeline coordinating camera buffer lifecycle with robotic arm pick-and-place waypoints.*

* **[SYS_02] AI Voice Control for Dobot** — [`suriyen-creator/Dobot_Voice_Control`](https://github.com/suriyen-creator/Dobot_Voice_Control)
  ```text
  [Microphone (.wav)] ──> [Faster-Whisper (CPU INT8)] ──> [Thai/English Fuzzy Match] ──> [Action Dispatch] ──> [Arm Pose Replay]
  ```
  *Offline speech recognition running locally on CPU to execute 11 command pairs without cloud latency.*

* **[SYS_03] AI Portfolio Reviewer** — [`suriyen-creator/ai-portfolio-reviewer`](https://github.com/suriyen-creator/ai-portfolio-reviewer) · [Live Streamlit App](https://ai-portfolio-reviewer-7romvlv56av4x9d2pcm3ar.streamlit.app)
  ```text
  [Resume PDF + GitHub API] ──> [Evidence Extraction] ──> [Google Gemini LLM] ──> [Streamlit Report]
  ```
  *Evidence-driven portfolio auditor cross-referencing resume claims with observable repository metadata.*

---

### 🖥️ Workstation & Rice Configuration

```bash
suriyen@workstation:~$ cat ~/.config/rice/environment.json
```

```json
{
  "system_rice": {
    "os_environment": "Windows Rice & Custom Utilities",
    "shell": "PowerShell 7 + Custom Rice Automation",
    "ricing_projects": [
      "suriyen-creator/6e5tz_window_rice",
      "suriyen-creator/HideTaskbar"
    ],
    "subdomain_service": "https://runs-on.dev/ (creator & maintainer)",
    "aesthetic": "TokyoNight Dark · Minimalist Cyber-Terminal · Physical Computing"
  }
}
```

---

### 📊 Language Distribution & Technologies

```bash
suriyen@workstation:~$ gh-stats --languages
```

```text
Python      [██████████████████████████████░░░░░░░░] 75.0%
PowerShell  [███████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░] 18.0%
JavaScript  [███░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░]  7.0%
```

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logo=ultralytics&logoColor=black" alt="YOLOv8" />
  <img src="https://img.shields.io/badge/Faster--Whisper-00A67E?style=flat-square&logo=openai&logoColor=white" alt="Faster-Whisper" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Dobot%20Magician-FF6F00?style=flat-square&logo=robot&logoColor=white" alt="Dobot" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell" />
</p>

---

```bash
suriyen@workstation:~$ ping -c 1 6e5tz.runs-on.dev
64 bytes from 6e5tz.runs-on.dev: icmp_seq=1 ttl=64 time=0.042 ms --- [HOST ONLINE]

suriyen@workstation:~$ ./contact.sh --endpoints
> Website:      https://6e5tz.runs-on.dev/
> GitHub:       https://github.com/suriyen-creator
> Free Domains: https://runs-on.dev/
```
