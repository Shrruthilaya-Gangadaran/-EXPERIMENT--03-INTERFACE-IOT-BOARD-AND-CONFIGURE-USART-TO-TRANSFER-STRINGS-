# EXPERIMENT--03-INTERFACING IOT BOARD AND CONFIGURE USART TO TRANSFER STRINGS
## AIM:
To Interface a iot board and to configure usart to transfer a string.

## COMPONENTS REQUIRED:
STM32 CUBE IDE, ARM IOT development board, STM programmer tool, Serial port utility tool.

## THEORY:
The full form of an ARM is an advanced reduced instruction set computer (RISC) machine, and it is a 32-bit processor architecture expanded by ARM holdings. The applications of an ARM processor include several microcontrollers as well as processors. The architecture of an ARM processor was licensed by many corporations for designing ARM processor-based SoC products and CPUs. This allows the corporations to manufacture their products using ARM architecture. Likewise, all main semiconductor companies will make ARM-based SOCs such as Samsung, Atmel, TI etc.

## PROCEDURE:
1. click on STM 32 CUBE IDE, the following screen will appear
 ![226189166-ac10578c-c059-40e7-8b80-9f84f64bf088](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/53768a24-e185-4c5e-b25b-58ec2817108e)

2. click on FILE, click on new stm 32 project![226189215-2d13ebfb-507f-44fc-b772-02232e97c0e3](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/99c180fd-e4ae-4822-9bb9-102693d26559)

![226189230-bf2d90dd-9695-4aaf-b2a6-6d66454e81fc](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/4c68ad13-d94d-438f-9c9f-a89753967103)

3. select the target to be programmed as shown below and click on next
![226189280-ed5dcf1d-dd8d-43ae-815d-491085f4863b](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/7f48d026-bc79-4728-98a9-fc7edd677d7f)

4. select the program name
![226189316-09832a30-4d1a-4d4f-b8ad-2dc28f137711](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/598a2612-60ef-4d42-9f97-dec37dc1bde8)

5. corresponding ioc file will be generated automatically
![226189378-3abbdee2-0df6-470f-a3cd-79c74e3d3ad8](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/0f5bf933-2c0c-4298-a632-ef6c9c152292)

6. select the appropriate pins as gipo, in or out, USART or required options and configure
![226189403-f7179f1a-3eae-4637-826b-ab4ec35ba1e1](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/0996e8ca-a5e9-487e-923f-9281e35cb082)
![226189425-2b2414ce-49b3-4b61-a260-c658cb2e4152](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/eab5fe37-eb23-411b-a1af-0f5fc8250533)

configure in the usart 2 as asynchronous mode and set the baud rate as 115200 as shown below
![234776631-d6a84ef4-904c-4eac-98ed-ab6253e9379c](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/5ff72686-56e8-421e-9b01-5d8448718c6c)

7. click on cntrl+S , automaticall C program will be generated
![226189443-8b43451d-0b14-47e4-a20b-cc09c6ad8458](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/9a2e2ebc-81bb-4462-aba3-0c0178b47e58)
![226189450-85ffa969-2ffb-4788-81e5-72d60fdda0f1](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/508fa0b5-31c5-49fb-af9b-4c5d3d6c9acc)

8. edit the program and as per required
   ![226189461-a573e62f-a109-4631-a250-a20925758fe0](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/2423d942-5f88-4ebf-a44f-813a3ba439b1)

9. use project and build all
    ![226189554-3f7101ac-3f41-48fc-abc7-480bd6218dec](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/5623054a-8d6d-42f8-b5b1-127ce9bce461)

10. URE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/7d02af65-f7e8-487d-ba1c-63e1ae48bd51)

 ![226189577-c61cc1eb-3990-4968-8aa6-aefffc766b70](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/1ef68d61-c34e-417d-a511-37c58283dbab)

11. once the project is bulild image![226189577-c61cc1eb-3990-4968-8aa6-aefffc766b70](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/37249cb5-d793-4fea-a3a8-a2f618f97b0c)

12. click on debug option
![226189625-37daa9a3-62e9-42b5-a5ce-2ac63345905b](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/7e1b6c08-2afe-4e76-8e94-abaccfa9ff15)

13. connect the ARM board to power supply and usb
14. check for execution of the output using run option

    
## STM 32 CUBE PROGRAM:
```C
#include "main.h"
#if defined (__ICCARM__) || defined (__ARMCC_VERSION)
#define PUTCHAR_PROTOTYPE int fputc(int ch, FILE *f)
#elif defined(__GNUC__)
#define PUTCHAR_PROTOTYPE int __io_putchar(int ch)
#endif /* __ICCARM__ || __ARMCC_VERSION */
UART_HandleTypeDef huart2;
void SystemClock_Config(void);
static void MX_GPIO_Init(void);
static void MX_USART2_UART_Init(void);

int main(void)
{
 
  HAL_Init();
  SystemClock_Config();
  MX_GPIO_Init();
  MX_USART2_UART_Init();
  while (1)
  {
	  printf("YUVARANI\n");
	  HAL_Delay(500);
  }
  
}
PUTCHAR_PROTOTYPE
{

  HAL_UART_Transmit(&huart2, (uint8_t *)&ch, 1, 0xFFFF);

  return ch;
}
void SystemClock_Config(void)
{
  RCC_OscInitTypeDef RCC_OscInitStruct = {0};
  RCC_ClkInitTypeDef RCC_ClkInitStruct = {0};
  __HAL_PWR_VOLTAGESCALING_CONFIG(PWR_REGULATOR_VOLTAGE_SCALE2);
  
  RCC_OscInitStruct.OscillatorType = RCC_OSCILLATORTYPE_MSI;
  RCC_OscInitStruct.MSIState = RCC_MSI_ON;
  RCC_OscInitStruct.MSICalibrationValue = RCC_MSICALIBRATION_DEFAULT;
  RCC_OscInitStruct.MSIClockRange = RCC_MSIRANGE_6;
  RCC_OscInitStruct.PLL.PLLState = RCC_PLL_NONE;
  if (HAL_RCC_OscConfig(&RCC_OscInitStruct) != HAL_OK)
  {
    Error_Handler();
  }
  
  RCC_ClkInitStruct.ClockType = RCC_CLOCKTYPE_HCLK3|RCC_CLOCKTYPE_HCLK
                              |RCC_CLOCKTYPE_SYSCLK|RCC_CLOCKTYPE_PCLK1
                              |RCC_CLOCKTYPE_PCLK2;
  RCC_ClkInitStruct.SYSCLKSource = RCC_SYSCLKSOURCE_MSI;
  RCC_ClkInitStruct.AHBCLKDivider = RCC_SYSCLK_DIV1;
  RCC_ClkInitStruct.APB1CLKDivider = RCC_HCLK_DIV1;
  RCC_ClkInitStruct.APB2CLKDivider = RCC_HCLK_DIV1;
  RCC_ClkInitStruct.AHBCLK3Divider = RCC_SYSCLK_DIV1;

  if (HAL_RCC_ClockConfig(&RCC_ClkInitStruct, FLASH_LATENCY_0) != HAL_OK)
  {
    Error_Handler();
  }
}

static void MX_USART2_UART_Init(void)
{
  huart2.Instance = USART2;
  huart2.Init.BaudRate = 115200;
  huart2.Init.WordLength = UART_WORDLENGTH_8B;
  huart2.Init.StopBits = UART_STOPBITS_1;
  huart2.Init.Parity = UART_PARITY_NONE;
  huart2.Init.Mode = UART_MODE_TX_RX;
  huart2.Init.HwFlowCtl = UART_HWCONTROL_NONE;
  huart2.Init.OverSampling = UART_OVERSAMPLING_16;
  huart2.Init.OneBitSampling = UART_ONE_BIT_SAMPLE_DISABLE;
  huart2.Init.ClockPrescaler = UART_PRESCALER_DIV1;
  huart2.AdvancedInit.AdvFeatureInit = UART_ADVFEATURE_NO_INIT;
  if (HAL_UART_Init(&huart2) != HAL_OK)
  {
    Error_Handler();
  }
  if (HAL_UARTEx_SetTxFifoThreshold(&huart2, UART_TXFIFO_THRESHOLD_1_8) != HAL_OK)
  {
    Error_Handler();
  }
  if (HAL_UARTEx_SetRxFifoThreshold(&huart2, UART_RXFIFO_THRESHOLD_1_8) != HAL_OK)
  {
    Error_Handler();
  }
  if (HAL_UARTEx_DisableFifoMode(&huart2) != HAL_OK)
  {
    Error_Handler();
  }
}

static void MX_GPIO_Init(void)
{
  __HAL_RCC_GPIOA_CLK_ENABLE();

}
void Error_Handler(void)
{
  __disable_irq();
  while (1)
  {
  }
 
}

#ifdef  USE_FULL_ASSERT

void assert_failed(uint8_t *file, uint32_t line)
{
  
}
#endif
```

## OUTPUT SCREENSHOTS OF SERIAL PORT UTILITY:
![IOT_EX03-1](https://github.com/kaviya2839/-EXPERIMENT--03-INTERFACING-A-SOIL-MOISTURE-SENSOR-AND-CONFIGURING-THE-OUTPUT-THROUGH-USART--USING-/assets/120553351/e31e98f7-ba84-4e06-bbad-4d905a9c6b1a)


## RESULT:
Interfacing a digital Input (Pushbutton ) with ARM microcontroller based IOT development is executed and the results are verified.
