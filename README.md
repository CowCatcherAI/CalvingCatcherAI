# CalvingCatcherAI
Following up CowCatcherAI with CalvingCatcherAI, this projects mainly revolves around monitoring the status around calving heifers or cows in the calving pen. Giving insights, information and notification with computervision and an integrated AI agent.

📷 Calving pen camera footage ──→ 🤖 AI Computer Vision ──→ ⚡ calving detection ──→ 💽 save image ──→ AI agent gives opinion and context ──→ 📲 Telegram notification with image and AI agent's reasoning

We are combining multiple existing open source technologies - for computer vision we are using YOLO from Ultralytics, for the Local AI agent we are using Qwen 3.0 and Moondream AI, which are trained with context around calving, or for less Local the API from any big LLM, and lastly the Telegram Bot

Latest update is using Ip camera with thermal lenses, This makes it possible to accurately detect the cow’s and newborn calf’s heat signatures, identify when a calf is being born, and perform a final check to confirm that the calf is alive.

Other Repo's from the Cowcatcher AI family

## Other Repo's from the Cowcatcher AI family
**Main repo
https://github.com/CowCatcherAI/CowCatcherAI

** AI detector (main software base)
https://github.com/ESchouten/ai-detector

**cowcatcher repo for in 100% python code 
https://github.com/JacobsFarm/CowCatcherAI-python

**Annotation Helper
https://github.com/JacobsFarm/annotation_helper_cowcatcherai

## 📄 License

This project uses the GNU Affero General Public License v3.0 (AGPL-3.0). It is based on Ultralytics YOLO and is fully open source.
IMPORTANT NOTICE: This software/model is NOT authorized for commercial use or distribution.

## 🙏 Acknowledgments

This project is made possible by the amazing [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) library. Their state-of-the-art computer vision technology forms the foundation for our AI detection of estrus behavior in cows.

**Thank you Ultralytics team!** 🚀 For making cutting-edge AI technology available that now also helps Dutch farmers.

## 🤝 Contributing

This is an open source project. You may modify and improve it as you see fit. Contributions are welcome via pull requests.
