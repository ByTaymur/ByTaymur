<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:0d1117,50:0b3d5c,100:00b4d8&text=Muhammed%20Taymur&fontColor=ffffff&fontSize=52&fontAlignY=38&desc=Mechatronics%20%7C%20Embedded%20%7C%20Power%20Electronics&descSize=18&descAlignY=60&animation=fadeIn" alt="Muhammed Taymur" width="100%"/>

<br/>
<sub><code>Firmware → PCB → Ürün · fikirden sahaya</code></sub>
<br/><br/>

![Rol](https://img.shields.io/badge/Rol-Mechatronics_Engineer-0d1117?style=flat-square&labelColor=0d1117&color=00b4d8)
![Odak](https://img.shields.io/badge/Odak-Gömülü_·_Güç_Elektroniği-0d1117?style=flat-square&labelColor=0d1117&color=00b4d8)

</div>

---

## `> whoami`

```c
typedef struct {
    const char *name;
    const char *role;
    const char *focus[4];
} Engineer_t;

const Engineer_t taymur = {
    .name    = "Muhammed Taymur",
    .role    = "Mekatronik Mühendisi",
    .focus   = { "Gömülü yazılım (STM32)",
                 "Güç elektroniği & motor kontrolü",
                 "PCB tasarımı",
                 "Mekatronik ürün geliştirme" },
};
```

Firmware yazıyor, güç elektroniği kartları tasarlıyor ve prototipleri çalışan ürüne dönüştürüyorum. Tasarımın sahada gerçekten çalışması benim için asıl ölçü.

---

## `> focus`

<table>
<tr>
<td width="50%" valign="top">

### 🔩 Gömülü Sistemler
STM32 ekosistemi (HAL / SPL), RTOS, düşük seviyeli sürücüler, hata ayıklama ve saha tanılama araçları.

### ⚡ Güç Elektroniği
IPM tabanlı sürücüler, indüksiyon ısıtma, güç kartı tasarımı ve doğrulaması.

</td>
<td width="50%" valign="top">

### 🌀 Motor Kontrolü
PMSM için FOC, sensörsüz kontrol (akademik yayın), akım/gerilim ölçüm zincirleri.

### 🧩 PCB & Ürün Geliştirme
KiCad ve Altium ile şematikten üretime; mekatronik ürünlerde donanım–yazılım–mekanik bütünlüğü.

</td>
</tr>
</table>

---

## `> stack`

| Alan | Araçlar |
|:--|:--|
| **Firmware** | `C` `C++` `FreeRTOS` `STM32 HAL / SPL` `Bootloader` |
| **Yazılım & Araç** | `Python` `TypeScript` `VS Code eklentileri` `MCP sunucuları` |
| **Donanım** | `STM32 / ARM Cortex-M` `RP2040` `Raspberry Pi` `Arduino` |
| **Tasarım** | `KiCad` `Altium Designer` `FreeCAD` `Fusion 360` `MATLAB / Simulink` |
| **Protokol** | `UART` `SPI` `I²C` `CAN` `MDB` `MQTT` `TCP/IP` |
| **Ölçüm** | `Saleae Logic` `Güç kalitesi / THD` |

---

## `> projects`

### 🤖 AI × Mühendislik

| Proje | Açıklama | Dil |
|:--|:--|:--:|
| [PcbAi](https://github.com/ByTaymur/PcbAi) | KiCad projelerini AI ajanlarına yerel MCP araçlarıyla açan çekirdek: şematik/kart okuma, ERC/DRC, PCB ölçümleri | `Python` |
| [CadAI](https://github.com/ByTaymur/CadAI) | Parçayı göster, değişikliği tarif et, gerisini AI yapsın. FreeCAD ve Fusion 360 adaptörleri | `Python` |
| [embedded-software-skills](https://github.com/ByTaymur/embedded-software-skills) | STM32 / Cortex-M firmware geliştirme için AI skill, slash komut ve ajan paketi | `Python` |
| [AiMonitor-LmStudio](https://github.com/ByTaymur/AiMonitor-LmStudio) | Uzak sunucuları ve LM Studio'yu izleyen açık kaynak izleme aracı | `Python` |

### 🛠️ Gömülü Geliştirme Araçları

| Proje | Açıklama | Dil |
|:--|:--|:--:|
| [stm32-professional-compiler](https://github.com/ByTaymur/stm32-professional-compiler) | VS Code / VSCodium için açık kaynak STM32 geliştirme ortamı | `TypeScript` |
| [ArmEditor](https://github.com/ByTaymur/ArmEditor) | ARM Cortex-M mikrodenetleyiciler için açık kaynak IDE | `C` |
| [STM32-Ultimate-Project-Setup-Tool](https://github.com/ByTaymur/STM32-Ultimate-Project-Setup-Tool) | STM32 projelerini hızlı ve düzenli kurmak için araç | `STM32` |
| [RPI-to-STM-Code-Upload](https://github.com/ByTaymur/RPI-to-STM-Code-Upload) | Raspberry Pi üzerinden bootloader ile STM32'ye kod yükleme | `C` |

### ⚡ Ölçüm & Protokol

| Proje | Açıklama | Dil |
|:--|:--|:--:|
| [differential-harmonic-analyzer](https://github.com/ByTaymur/differential-harmonic-analyzer) | KCL ile şebekeden izole THD ölçümü yapan DIY harmonik analizör | `Python` |
| [MDB-Protocol-Decoder](https://github.com/ByTaymur/MDB-Protocol-Decoder) | Saleae Logic için MDB çözücü: cashless, coin changer, bill validator | `Python` |

**Diğer:** [I2C_MCP23017_DMA](https://github.com/ByTaymur/I2C_MCP23017_DMA) · [WS2812Stm32f446](https://github.com/ByTaymur/WS2812Stm32f446) · [TcpIp-Gsm.Stm32](https://github.com/ByTaymur/TcpIp-Gsm.Stm32) · [Oyuncak_Rp2040](https://github.com/ByTaymur/Oyuncak_Rp2040)

---

## `> interests`

`AI ajanları × mühendislik araçları (MCP)` · `Motor kontrolü (FOC)` · `Güç kalitesi ölçümü` · `Gömülü geliştirme araçları` · `Vending protokolleri (MDB)` · `RTOS` · `LiDAR`

---

## `> contact`

<div align="center">

[![E-posta](https://img.shields.io/badge/E--posta-tymr.mhe@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=00b4d8&labelColor=0d1117&color=00b4d8)](mailto:tymr.mhe@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-ByTaymur-0d1117?style=for-the-badge&logo=github&logoColor=00b4d8&labelColor=0d1117&color=00b4d8)](https://github.com/ByTaymur)

<sub>Projelerimi faydalı bulduysan ⭐ bırakman çok kıymetli.</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:00b4d8,50:0b3d5c,100:0d1117&section=footer" width="100%" alt=""/>

<div align="center"><sub>© 2026 Muhammed Taymur · Mechatronics Engineer</sub></div>
