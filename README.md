# Kontrol Algoritmaları (Control Algorithms)

Bu proje, kontrol sistemleri ve algoritmalarının öğretici bir yaklaşımla sunulmasını amaçlamaktadır. Jupyter notebook'ları aracılığıyla farklı kontrol yöntemlerinin teorik temelleri ve Python simülasyonları ile pratik uygulamaları incelenmektedir.

## İçindekiler

### Temel Kontrol Algoritmaları
- **01_pid_control.ipynb** - PID (Oransal-İntegral-Türevsel) Kontrol
- **02_lead_lag_control.ipynb** - Lead-Lag Kompanzatör Tasarımı
- **03_state_feedback_control.ipynb** - Durum Geri Beslemeli Kontrol
- **04_lqr_control.ipynb** - Lineer Kuadratik Regülatör (LQR)
- **05_model_predictive_control.ipynb** - Model Öngörülü Kontrol (MPC)

### İleri Kontrol Teknikleri
- **06_adaptive_control_mrac.ipynb** - Adaptif Kontrol (MRAC)
- **07_fuzzy_logic_control.ipynb** - Bulanık Mantık Kontrolü
- **08_neural_network_control.ipynb** - Yapay Sinir Ağı ile Kontrol
- **09_rl_control.ipynb** - Pekiştirmeli Öğrenme ile Kontrol

### Gelişmiş Kontrol Yöntemleri
- **10_sliding_mode_control.ipynb** - Kayan Kipli Kontrol
- **11_feedback_linearization.ipynb** - Geri Besleme Doğrusallaştırma
- **12_robust_control_hinf.ipynb** - Gürbüz Kontrol (H-infinity)
- **13_backstepping_control.ipynb** - Backstepping Kontrolü
- **14_lyapunov_based_control.ipynb** - Lyapunov Tabanlı Kontrol

### Dijital ve Öz-Ayarlama
- **15_digital_control_zdomain.ipynb** - Dijital Kontrol (Z-Domain)
- **16_self_tuning_regulator.ipynb** - Öz-Ayarlı Regülatör
- **17_lqg_control.ipynb** - Lineer Kuadratik Gaussian (LQG) Kontrol

## Kurulum

### Gereksinimler
Python 3.x ve aşağıdaki kütüphaneler gereklidir:

```bash
pip install -r requirements.txt
```

### Gerekli Kütüphaneler
- numpy
- scipy
- matplotlib
- control
- cvxpy
- gym
- scikit-fuzzy
- stable-baselines3

## Kullanım

1. Depoyu klonlayın:
```bash
git clone https://github.com/kurpeeren/control-algorithms.git
cd control-algorithms
```

2. Bağımlılıkları yükleyin:
```bash
pip install -r requirements.txt
```

3. Jupyter notebook'larını çalıştırın:
```bash
jupyter notebook
```

4. `notebooks/` klasöründeki ilgili notebook'u açın.

## Google Colab

Notebook'ları doğrudan Google Colab'da açmak için her notebook'un başındaki "Open in Colab" butonunu kullanabilirsiniz.

## Proje Yapısı

```
control-algorithms/
├── README.md
├── requirements.txt
└── notebooks/
    ├── 01_pid_control.ipynb
    ├── 02_lead_lag_control.ipynb
    ├── ...
    └── 17_lqg_control.ipynb
```

## Katkıda Bulunma

Katkılarınızı bekliyoruz! Lütfen pull request göndermeden önce mevcut kod stiline uygun olduğunuzdan emin olun.

## Lisans

Bu proje eğitim amaçlıdır.
