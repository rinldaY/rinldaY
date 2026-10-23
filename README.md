<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=rinldaY&fontSize=70&fontColor=00e5ff&animation=fadeIn&fontAlignY=38&desc=AI%20%C3%97%20Chemical%20Process%20Monitoring&descAlignY=58&descSize=18" width="100%"/>

<a href="https://github.com/rinldaY">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=00E5FF&center=true&vCenter=true&width=620&lines=%3E+detecting+anomalies+in+chemical+reactors;%3E+PCA+%2B+LSTM+%3D+T%C2%B2-LSTM;%3E+no+data+leakage.+no+hardcoded+results.;%3E+73+tests+passed+%E2%9C%85" alt="typing" />
</a>

![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

</div>

---

## 👋 สวัสดี

```python
class RinldaY:
    focus    = ["Anomaly Detection", "Time-series", "Deep Learning", "MSPC"]
    domain   = "Chemical Process × AI"
    mindset  = "ผลลัพธ์ต้องมาจากการรันจริง ไม่ใช่การเดา"
    currently = "วิจัยแบบจำลอง T²-LSTM บน Tennessee Eastman Process"
```

## 🔥 โปรเจกต์เด่น

### 🧪 [AIChemical](https://github.com/rinldaY/AIChemical)
> ระบบตรวจจับความผิดปกติของเตาปฏิกรณ์เคมีด้วย AI บนชุดข้อมูลมาตรฐาน **Tennessee Eastman Process (TEP)**

เปรียบเทียบ 5 แบบจำลอง ตั้งแต่ Rule-based ไปจนถึง Hybrid:

| Model | แนวคิด |
|:--|:--|
| 📏 Fixed Threshold (3σ) | Baseline แบบกฎตายตัว |
| 📉 PCA / Hotelling's T² + SPE | Multivariate SPC |
| 🧠 Deep Autoencoder | Reconstruction error |
| 🔁 Stacked LSTM | จับพลวัตเชิงเวลา |
| ⚡ **T²-LSTM (Proposed)** | LSTM latent space + Hotelling's T² + SPE |

**จุดที่ภูมิใจ**
- 🛡️ แบ่งข้อมูลตาม `simulationRun` เข้มงวด ไม่มี window คร่อม run
- 🧼 Train ด้วยข้อมูลปกติ 100% และ fit scaler จาก train เท่านั้น
- ✅ Unit tests 73 ข้อ ผ่านทั้งหมด
- 📊 ตัวเลข benchmark มาจาก `run_benchmark.py` จริง ไม่มี hardcode

<div align="center">

[![AIChemical](https://github-readme-stats.vercel.app/api/pin/?username=rinldaY&repo=AIChemical&theme=tokyonight&hide_border=true)](https://github.com/rinldaY/AIChemical)

</div>

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pytest](https://img.shields.io/badge/-pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

## 🎯 กำลังสนใจ

- 🔬 Hybrid model ที่รวมความเข้มงวดของสถิติเข้ากับพลังของ Deep Learning
- ⏱️ การลด False Alarm Rate โดยไม่เสียความไวในการตรวจจับ
- 📐 Evaluation ที่ซื่อตรง: FDR, FAR, AUROC, Detection Delay

## 📫 ติดต่อ

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-rinldaY-181717?style=for-the-badge&logo=github)](https://github.com/rinldaY)
<!-- เพิ่มช่องทางที่ต้องการ -->
<!-- [![Email](https://img.shields.io/badge/Email-you@mail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:you@mail.com) -->
<!-- [![LinkedIn](https://img.shields.io/badge/LinkedIn-your--name-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-name) -->

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%"/>
