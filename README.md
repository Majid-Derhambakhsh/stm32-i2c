# stm32-i2c
Driver for modifying HAL-I2C library of STM32 microcontroller to support Px memory bit in device address.

#### Version : 0.0.0

- #### Type : Embedded Software.

- #### Support : STM32 series.

- #### Program Language : C/C++

- #### Properties :

- #### Functions :
```c++ 
HAL_StatusTypeDef HAL_I2C_Mem_Read2(I2C_HandleTypeDef *hi2c, uint16_t DevAddress, uint16_t MemAddress, uint16_t MemAddSize, uint8_t *pData, uint16_t Size, uint32_t Timeout)
HAL_StatusTypeDef HAL_I2C_Mem_Write2(I2C_HandleTypeDef *hi2c, uint16_t DevAddress, uint16_t MemAddress, uint16_t MemAddSize, uint8_t *pData, uint16_t Size, uint32_t Timeout)
HAL_StatusTypeDef HAL_I2C_Mem_Erase(I2C_HandleTypeDef *hi2c, uint16_t DevAddress, uint16_t MemAddress, uint16_t MemAddSize, uint16_t Size, uint32_t stwc, uint32_t Timeout)
```
#### Developer: Majid Derhambakhsh
