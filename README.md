# 🚌 공공데이터를 이용한 세종시 BRT 버스 정류장 최적화
DSC 공유대학 모빌리티 캡스톤 디자인Ⅱ
## 🗓️ 프로젝트 기간
2023/9/5 ~ 2023/12/12
## 🧑‍💻 프로젝트 인원
주재만, 김세은, 조유빈
## 👤 내 역할
- 데이터 수집
- Google Colab, Jupyter Notebook, Python 및 QGIS, Mapbox 이용해 데이터 필터링, 분석, 시각화 및 전처리
- 회귀 및 MCLP(Maximal Covering Location Problem) 기반 BRT 버스 정류장 최적 입지 선정 알고리즘 구현
## 🛠️ 사용 언어 및 기술
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/QGIS-3A6E3A?style=flat-square&logo=qgis&logoColor=white"/> <img src="https://img.shields.io/badge/Mapbox-000000?style=flat-square&logo=mapbox&logoColor=white"/> <img src="https://img.shields.io/badge/Google Colab-F9AB00?style=flat-square&logo=google-colab&logoColor=white"/>

## 💫 설명
![슬라이드1](https://github.com/user-attachments/assets/2162c73a-9482-45c2-9d9d-b0629b14b553)
![슬라이드2](https://github.com/user-attachments/assets/5cf4ad59-8f17-4b21-8001-2722636e286f)
![슬라이드3](https://github.com/user-attachments/assets/6996f2ad-a18b-4d18-a45c-01e3ab992945)
![슬라이드4](https://github.com/user-attachments/assets/5393e3d2-dcd2-49df-a0da-fa40042da34a)
![슬라이드5](https://github.com/user-attachments/assets/4ff8255a-6fcf-4e30-b81a-72beb454f528)
![슬라이드6](https://github.com/user-attachments/assets/073aa7da-5e87-4596-b66c-3e4742a7a385)
![슬라이드7](https://github.com/user-attachments/assets/1443d982-3099-4c26-856a-6a7392d456e1)
![슬라이드8](https://github.com/user-attachments/assets/d68a0ee8-9d34-4689-b4e4-dd1cc06534e9)
![슬라이드9](https://github.com/user-attachments/assets/2802c0e6-bef0-4697-ae8e-8c4e1a39bb31)
![슬라이드10](https://github.com/user-attachments/assets/3ad44815-c02d-4bab-8d47-85444097f3e8)
![슬라이드11](https://github.com/user-attachments/assets/c7346582-f931-4899-8685-db8fd8ed8847)
![슬라이드12](https://github.com/user-attachments/assets/6555f16d-77e2-4e54-a22b-8b46f39050e1)
![슬라이드13](https://github.com/user-attachments/assets/3613d9bf-d7a7-4be3-a26d-7163ea83a345)
![슬라이드14](https://github.com/user-attachments/assets/16edc87f-0a37-4ac2-9c82-6df21d4ded56)
![슬라이드15](https://github.com/user-attachments/assets/15ff0e89-4ee7-4a71-9f2d-210e4dfc3ccf)
![슬라이드16](https://github.com/user-attachments/assets/d0cd4871-55fe-45ff-ba47-b7b255c5ed37)
![슬라이드17](https://github.com/user-attachments/assets/4f4ccfdc-a970-4dfa-913d-cdfbc85cc260)
![슬라이드18](https://github.com/user-attachments/assets/581b5e13-2d8d-4932-a0a6-545cc3ac2162)
![슬라이드19](https://github.com/user-attachments/assets/3341eaab-5fe0-4545-bd67-dbb91dba2140)
![슬라이드20](https://github.com/user-attachments/assets/6400037a-3ddc-4e92-87c3-f663004326f8)
![슬라이드21](https://github.com/user-attachments/assets/5dcf4124-4285-454e-88c4-fca2b4744203)
![슬라이드22](https://github.com/user-attachments/assets/6455ab95-a860-4fd0-ac3c-e7f29044d916)
![슬라이드23](https://github.com/user-attachments/assets/635ae173-328f-49a2-9960-9c444343ca86)
![슬라이드24](https://github.com/user-attachments/assets/081f3292-8c3a-4365-a51f-b8b6504ca772)
![슬라이드25](https://github.com/user-attachments/assets/2745c646-4c70-452b-9ac7-46603403928d)
![슬라이드26](https://github.com/user-attachments/assets/b6ec27ee-bba1-4799-8666-a459384cffb3)
![슬라이드27](https://github.com/user-attachments/assets/c82ac83c-fc17-4c18-aa5e-483819ced7f9)
![슬라이드28](https://github.com/user-attachments/assets/c932c17a-b820-483e-84bf-c8778fb1d1d9)
![슬라이드29](https://github.com/user-attachments/assets/47453699-240a-42e0-a682-e338dffc7fe7)
![슬라이드30](https://github.com/user-attachments/assets/f87f7957-2ecd-4d17-9412-209797c77c7b)
![슬라이드31](https://github.com/user-attachments/assets/8e091388-8e3c-49b0-b483-2969a3597654)
![슬라이드32](https://github.com/user-attachments/assets/3aaa66a7-1fc7-4303-a3ca-7aef80090eaa)
![슬라이드33](https://github.com/user-attachments/assets/26cca981-30e5-4e2e-be14-00ba76d13387)
![슬라이드34](https://github.com/user-attachments/assets/ebbd4a44-8e6a-4213-8294-dfc5a12bf2e3)
![슬라이드35](https://github.com/user-attachments/assets/87101d84-5b74-4573-b659-1992d0493ab5)
![슬라이드36](https://github.com/user-attachments/assets/b73df7b4-1318-4c07-b066-49ca322fe73a)
![슬라이드37](https://github.com/user-attachments/assets/1adadf81-b807-4e00-8745-66078b4626be)
![슬라이드38](https://github.com/user-attachments/assets/8f965778-e186-4e1b-a21c-985b2404fdd0)
![슬라이드39](https://github.com/user-attachments/assets/8dca97be-67f9-4b38-8121-24ea3638a3a6)
![슬라이드40](https://github.com/user-attachments/assets/25203e28-e18d-4f22-85b5-2983392d07bb)
![슬라이드41](https://github.com/user-attachments/assets/b8c62f6d-33eb-4878-8853-b4404ec0441a)
![슬라이드42](https://github.com/user-attachments/assets/39b2d281-390c-44b0-b317-a51adb80d9d0)
![슬라이드43](https://github.com/user-attachments/assets/3a434301-557c-4a7f-a57f-a55ed8186608)
![슬라이드44](https://github.com/user-attachments/assets/b258e1c2-8caf-43a7-a63e-e053d73ed4b6)
![슬라이드45](https://github.com/user-attachments/assets/47fe7613-410e-4ae2-aa54-85a83f0e2769)
![슬라이드46](https://github.com/user-attachments/assets/3583488c-89af-480f-bc77-5b31e4b71082)
![슬라이드47](https://github.com/user-attachments/assets/bb86817c-c8d9-4edf-8cb8-ce7e4f9dc948)
![슬라이드48](https://github.com/user-attachments/assets/f043185c-dc67-4668-bb3e-c7c2c4b07091)
![슬라이드49](https://github.com/user-attachments/assets/dbbf7ec9-9cc0-4da6-94ee-8d84d929b5bb)
![슬라이드50](https://github.com/user-attachments/assets/4530a816-0fe6-4e7d-a13e-232c6bb213c5)
![슬라이드51](https://github.com/user-attachments/assets/b9031df9-1c68-484b-ab72-36cd916d7a4f)
![슬라이드52](https://github.com/user-attachments/assets/dcf0e24c-60be-4e57-96d7-8d8668d3c695)
![슬라이드53](https://github.com/user-attachments/assets/ee55abf8-6810-434b-a953-a1ef04ca5c98)
![슬라이드54](https://github.com/user-attachments/assets/7827211b-5fb3-4b38-a3bd-ac0f4841e7db)
![슬라이드55](https://github.com/user-attachments/assets/73e4e682-0004-40ba-b73a-43a8c2251def)
![슬라이드56](https://github.com/user-attachments/assets/99e50133-b43f-4030-ab80-3d1af62b404e)
![슬라이드57](https://github.com/user-attachments/assets/60a23753-5c4d-498b-a0b4-f1d3ad1bc818)
![슬라이드58](https://github.com/user-attachments/assets/5b6fa3cf-3cab-4881-910a-6273efc9ee6a)
![슬라이드59](https://github.com/user-attachments/assets/0ee1af59-875a-4f03-981e-434e7e83208f)
![슬라이드60](https://github.com/user-attachments/assets/9ada9288-5f69-414f-bac3-749ccfd4afd9)
![슬라이드61](https://github.com/user-attachments/assets/3f48871f-2ffe-4d14-bc65-ec27ed972153)
## 🌟 기타
용량이 너무 커서 못 올린 파일들  
👉 https://drive.google.com/drive/folders/1z_cjeVDWF4VA2Epbp4ymbgw6A2gEZHmQ?usp=sharing
