https://www.amobbs.com/thread-5603206-1-1.html?_dsign=e1873422

晶体12m

IAR版本:EWARM-CD-7403-8938

项目位置:STM32F105_VCP\Project\USB_Device_Examples\VCP\EWARM\usbd_vcp.eww

主要修改内容：
硬件上面：DP上拉到USB 5V，我接的是10k，根据官方说法1.5k比较好）


应用程序位置：
usbd_cdc_vcp.c     
发送函数：static uint16_t VCP_DataTx (uint8_t* Buf, uint32_t Len)
接收回调函数： static uint16_t VCP_DataRx (uint8_t* Buf, uint32_t Len)



