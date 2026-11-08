<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0d1117,50:0b3d5c,100:00b4d8&text=Muhammed%20Taymur&fontColor=ffffff&fontSize=52&fontAlignY=40&desc=System%20Architecture%20%C2%B7%20Integration%20%C2%B7%20AI%20Agents&descSize=18&descAlignY=62&animation=fadeIn" alt="Muhammed Taymur — Mechatronics engineer: system architecture, integration, AI agents and MCP bridges for hardware" width="100%"/>

**Sistem Mimarisi** · **Entegrasyon** · **AI Ajanları & MCP** · Agent Skills · Mekatronik

</div>

---

## `> about`

**Muhammed Taymur — Mekatronik mühendisi.** İşimin merkezi sistem mimarisi ve entegrasyon: mekanik, elektronik, gömülü yazılım, saha operasyonu ve yapay zekâyı tek bir çalışan sisteme bağlamak.

Son dönemdeki odağım, LLM ajanlarının gerçek mühendislik araçlarını ve donanımı kullanabilmesi. KiCad, FreeCAD / Fusion 360, OpenOCD ve mikrodenetleyici RAM / register'ları için MCP köprüleri kuruyor; ajanlar için skill, komut ve iş akışı paketleri tasarlıyorum. Hedefim, mekanik tasarım, devre ve yazılımın tek bir ajan tarafından senkron geliştirilebildiği ve açık kaynak / yerel LLM'lerle çalışan bir altyapı.

**EN:** Mechatronics engineer working on system architecture and integration — tying mechanics, electronics, firmware, field operations and AI into one working system. I build MCP bridges and agent skills that let LLM agents use real engineering tools and hardware (KiCad, FreeCAD / Fusion 360, OpenOCD, MCU memory), aiming for a stack where one agent develops mechanics, circuits and software in sync — on open-source / local LLMs.

---

## `> what-i-build`

| Alan | Ne yapıyorum | Kanıt |
|:--|:--|:--|
| **AI ajanları & MCP entegrasyonu** | Mühendislik araçlarını ve donanımı LLM ajanlarına açan MCP sunucuları; ajanın donanımla doğrudan, register / RAM seviyesinde çalışabilmesi | [PcbAi](https://github.com/ByTaymur/PcbAi), [CadAI](https://github.com/ByTaymur/CadAI) |
| **Agent skill & iş akışı tasarımı** | Ajanlar için skill, slash komut ve alt ajan paketleri; bulut + yerel LLM'i birlikte kullanan geliştirme akışları | [embedded-software-skills](https://github.com/ByTaymur/embedded-software-skills) |
| **Sistem mimarisi & entegrasyon** | Makine seviyesinde mimari: kontrol kartı, güç katı, HMI, ödeme sistemi (MDB), üçüncü parti modüller ve uzaktan erişimin tek sistemde birleşmesi | [MDB-Protocol-Decoder](https://github.com/ByTaymur/MDB-Protocol-Decoder), [RPI-to-STM-Code-Upload](https://github.com/ByTaymur/RPI-to-STM-Code-Upload) |
| **Operasyon otomasyonu** | Üretim, satın alma, arıza ve görev akışlarını özetleyip planlayan ajanlar; sahadaki makineler için 7/24 teşhis ajanı | Kapalı kaynak |
| **Geliştirici araçları** | IDE, VS Code eklentileri, proje kurulum ve sistem izleme araçları | [stm32-professional-compiler](https://github.com/ByTaymur/stm32-professional-compiler), [ArmEditor](https://github.com/ByTaymur/ArmEditor), [AiMonitor-LmStudio](https://github.com/ByTaymur/AiMonitor-LmStudio) |
| **Donanım temeli** | Gömülü yazılım (STM32), güç elektroniği, motor kontrolü (FOC), PCB, güç kalitesi ölçümü | [differential-harmonic-analyzer](https://github.com/ByTaymur/differential-harmonic-analyzer), sensörsüz PMSM kontrolü üzerine akademik yayın |

---

## `> now`

- **Saha operatör ajanı** — Sahadaki makinelere uzaktan (Raspberry Pi → OpenOCD → SWD) bağlanan, hataları analiz edip müdahale senaryosu üreten ve makineyi servise döndüren, IoT paneline entegre 7/24 ajan. *(kapalı kaynak)*
- **OpenOCD → MCP** — Ajanların debug probe üzerinden mikrodenetleyiciyle doğrudan çalışması.
- **Linux çekirdeği → MCP** — RAM'i okuyup anlamlandıran, uzun süren işleri izleyen derin entegrasyon. *(planlanıyor)*
- **PcbAi + CadAI** — Mekanik, devre ve yazılımın tek ajanla senkron geliştirilmesi; yerel LLM ile çalışacak şekilde.

---

## `> stack`

| Alan | Araçlar |
|:--|:--|
| **AI & ajanlar** | `MCP` `Claude Code` `Agent skills` `LM Studio` `Yerel LLM (Qwen)` `Gemini / Workspace Studio` |
| **Entegrasyon & yazılım** | `Python` `TypeScript` `VS Code eklentileri` `IoT panel` `Raspberry Pi` |
| **Gömülü & debug** | `C` `C++` `STM32 / ARM Cortex-M` `FreeRTOS` `OpenOCD / SWD` `Bootloader` |
| **Tasarım** | `KiCad` `Altium Designer` `FreeCAD` `Fusion 360` `MATLAB / Simulink` |
| **Protokol** | `UART` `SPI` `I²C` `CAN` `MDB` `MQTT` `TCP/IP` |

---

## `> projects`

| Proje | Açıklama | Dil |
|:--|:--|:--:|
| **🤖 AI Ajanları & MCP** | | |
| [PcbAi](https://github.com/ByTaymur/PcbAi) | KiCad projelerini AI ajanlarına yerel MCP araçlarıyla açan çekirdek: şematik/kart okuma, ERC/DRC, PCB ölçümleri | `Python` |
| [CadAI](https://github.com/ByTaymur/CadAI) | Parçayı göster, değişikliği tarif et, gerisini AI yapsın. FreeCAD ve Fusion 360 adaptörleri | `Python` |
| [embedded-software-skills](https://github.com/ByTaymur/embedded-software-skills) | Gömülü yazılım ajanları için skill, slash komut ve alt ajan paketi | `Python` |
| [AiMonitor-LmStudio](https://github.com/ByTaymur/AiMonitor-LmStudio) | Uzak sunucuları ve LM Studio'yu izleyen açık kaynak izleme aracı | `Python` |
| **🛠️ Geliştirici Araçları** | | |
| [stm32-professional-compiler](https://github.com/ByTaymur/stm32-professional-compiler) | VS Code / VSCodium için açık kaynak STM32 geliştirme ortamı | `TypeScript` |
| [ArmEditor](https://github.com/ByTaymur/ArmEditor) | ARM Cortex-M mikrodenetleyiciler için açık kaynak IDE | `C` |
| [STM32-Ultimate-Project-Setup-Tool](https://github.com/ByTaymur/STM32-Ultimate-Project-Setup-Tool) | STM32 projelerini hızlı ve düzenli kurmak için araç | `STM32` |
| **🔌 Entegrasyon, Ölçüm & Protokol** | | |
| [MDB-Protocol-Decoder](https://github.com/ByTaymur/MDB-Protocol-Decoder) | Saleae Logic için MDB çözücü: cashless, coin changer, bill validator | `Python` |
| [RPI-to-STM-Code-Upload](https://github.com/ByTaymur/RPI-to-STM-Code-Upload) | Raspberry Pi üzerinden bootloader ile STM32'ye kod yükleme | `C` |
| [differential-harmonic-analyzer](https://github.com/ByTaymur/differential-harmonic-analyzer) | KCL ile şebekeden izole THD ölçümü yapan DIY harmonik analizör | `Python` |

**Diğer:** [I2C_MCP23017_DMA](https://github.com/ByTaymur/I2C_MCP23017_DMA) · [WS2812Stm32f446](https://github.com/ByTaymur/WS2812Stm32f446) · [TcpIp-Gsm.Stm32](https://github.com/ByTaymur/TcpIp-Gsm.Stm32) · [Oyuncak_Rp2040](https://github.com/ByTaymur/Oyuncak_Rp2040)

---

## `> interests`

`Ajan mimarileri` · `MCP & tool-use` · `Yerel / açık kaynak LLM'ler` · `Donanım-in-the-loop AI` · `Sistem entegrasyonu` · `Motor kontrolü (FOC)` · `Güç kalitesi`

---

## `> contact`

📧 [tymr.mhe@gmail.com](mailto:tymr.mhe@gmail.com) · 🐙 [github.com/ByTaymur](https://github.com/ByTaymur)

Projelerimi faydalı bulduysan ⭐ bırakman çok kıymetli.

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:00b4d8,50:0b3d5c,100:0d1117&section=footer" width="100%" alt=""/>
