# HW-SPI-FLASH
## W25Q16JV entegresi kullanarak Altium üzerinden modül tasarımı
Kullanılan kartlarda ek hafıza birimi oluşturmak, projelerde kullanılan ses ve görüntü gibi dosyaların içerisine yazılması ile mikrodenetleyici 
tarafından çeklmesiyle mikrodenetleyici hafızasında ek alan kaplanmasının önüne geçilmesini sağlamaktadır.

## W25Q16JVSSIQ TR PIN

| Sembol                | Pin | I/O | Açıklama |
| ------                | --- | --- | -------- |
|  /CS                  |  1  |  I  |Çip Seçim Girişi |
|  DO (IO1)             |  2  | I/O |Veri Çıkışı (Veri Giriş Çıkışı 1) |
|  /WP (IO2)            |  3  | I/O |Yazmaya Karşı Koruma Girişi (Veri Girişi Çıkış 2) |
|  GND                  |  4  |     |Topraklama|
| DI (IO0)              |  5  | I/O |Veri Girişi (Veri Giriş Çıkışı 0) |
| CLK                   |  6  |  I  |Seri Saat Girişi |
| /HOLD or /RESET (IO3) |  7  | I/O |Tutma veya Sıfırlama Girişi (Veri Girişi Çıkış 3)|
|   VCC                 |  8  |     |Güç girişi |

## Komponentler
- W25Q16JV 
- 0.1  µF kondansatör
  
## Şematik
![spiflash_schematics](https://github.com/KOBASTAR-IME-2024/SPI_FLASH_HW/assets/119225109/7df01df1-3a76-4d60-b50f-b40c370366d1)
## PCB
![SPI_Flash_PCB](https://github.com/KOBASTAR-IME-2024/SPI_FLASH_HW/assets/119225109/c1fc1e88-af6e-4fa2-966e-b20afb2c62f8)

![SPI_Flash_PCB_visible](https://github.com/KOBASTAR-IME-2024/SPI_FLASH_HW/assets/119225109/dc133083-c056-4083-adf6-fbfc6cc94abd)
## PCB 3D
![spiflash](https://github.com/KOBASTAR-IME-2024/SPI_FLASH_HW/assets/119225109/dee518f4-d15b-4220-9e0c-c8c848022e36)
![spiflash_back](https://github.com/KOBASTAR-IME-2024/SPI_FLASH_HW/assets/119225109/c24c948e-2cf7-4863-8ca9-e4fe00602009)


