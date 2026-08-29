ESP32-S3-N16R8使用TFT_eSPI库出现白屏,lib/TFT_eSPI-2.5.43/Processors/TFT_eSPI_ESP32_S3.h这个地方的第83行的#define SPI_PORT FSPI必须改成#define SPI_PORT 2就可以解决
