# Document - USB Audio Function Trace #
## Table of Contents ##

### Filename - usbdmain.c ###
Description - Function List with detail description
Arranged in order of Declaration.

##### void get\_potval (void) #####


---


##### void TIMER0\_IRQHandler(void) #####


---


##### int main (void) #####


---


### Filename - usbhw.c ###
Description - Function List with detail description			Arranged in order of declaration.

##### uint32\_t EPAdr (uint32\_t EPNum) #####


---


##### void WrCmd (uint32\_t cmd) #####


---


##### void WrCmdDat (uint32\_t cmd, uint32\_t val) #####


---


##### void WrCmdEP (uint32\_t EPNum, uint32\_t cmd) #####


---


##### uint32\_t RdCmdDat(uint32\_t cmd) #####


---


##### void USB\_Init(void) #####


---


##### void USB\_Connect(uint32\_t con) #####


---


##### void USB\_Reset(void) #####


---


##### void USB\_Suspend (void) #####


---


##### void USB\_Resume (void) #####


---


##### void USB\_WakeUp (void) #####


---


##### void USB\_WakeUpCfg (uint32\_t cfg) #####


---


##### void USB\_SetAddress (uint32\_t adr) #####


---


##### void USB\_Configure (uint32\_t cfg) #####


---


##### void USB\_ConfigEP (USB\_ENDPOINT\_DESCRIPTOR **pEPD) #####**


---


##### void USB\_DirCtrlEP (uint32\_t dir) #####


---


##### void USB\_EnableEP (uint32\_t EPNum) #####


---


##### void USB\_DisableEP (uint32\_t EPNum) #####


---


##### void USB\_ResetEP (uint32\_t EPNum) #####


---


##### void USB\_SetStallEP (uint32\_t EPNum) #####


---


##### void USB\_ClrStallEP (uint32\_t EPNum) #####


---


##### void USB\_ClearEPBuf (uint32\_t EPNum) #####


---


##### uint32\_t USB\_ReadEP (uint32\_t EPNum, uint8\_t **pData) #####**


---


##### uint32\_t USB\_WriteEP (uint32\_t EPNum, uint8\_t **pData, uint32\_t cnt) #####**


---


##### uint32\_t USB\_DMA\_Setup(uint32\_t EPNum, USB\_DMA\_DESCRIPTOR **pDD) #####**


---


##### void USB\_DMA\_Enable (uint32\_t EPNum) #####


---


##### void USB\_DMA\_Disable (uint32\_t EPNum) #####


---


##### uint32\_t USB\_DMA\_Status (uint32\_t EPNum) #####


---


##### uint32\_t USB\_DMA\_BufAdr (uint32\_t EPNum) #####


---


##### uint32\_t USB\_DMA\_BufCnt (uint32\_t EPNum) #####


---


##### uint32\_t USB\_GetFrame (void) #####


---


##### void USB\_IRQHandler (void) #####


---


### Filename - usbcore.c ###
Description - Function List with detail description
Arranged in order of declaration.

##### void USB\_ResetCore (void) #####


---


##### void USB\_SetupStage (void) #####


---


##### void USB\_DataInStage (void) #####


---


##### void USB\_DataOutStage (void) #####


---


##### void USB\_StatusInStage (void) #####


---


##### void USB\_StatusOutStage (void) #####


---


##### inline uint32\_t USB\_ReqGetStatus (void) #####


---


##### inline uint32\_t USB\_ReqSetClrFeature (uint32\_t sc) #####


---


##### inline uint32\_t USB\_ReqSetAddress (void) #####


---


##### inline uint32\_t USB\_ReqGetDescriptor (void) #####


---


##### inline uint32\_t USB\_ReqGetConfiguration (void) #####


---


##### inline uint32\_t USB\_ReqSetConfiguration (void) #####


---


##### inline uint32\_t USB\_ReqGetInterface (void) #####


---


##### inline uint32\_t USB\_ReqSetInterface (void) #####


---


##### void USB\_EndPoint0 (uint32\_t event) #####


---


### Filename - usbuser.c ###
Description - Function List with detail description			Arranged in order of declaration.

##### void USB\_Power\_Event (uint32\_t  power) #####


---


##### void USB\_Reset\_Event (void) #####


---


##### void USB\_Suspend\_Event (void) #####


---


##### void USB\_Resume\_Event (void) #####


---


##### void USB\_WakeUp\_Event (void) #####


---


##### void USB\_SOF\_Event (void) #####


---


##### void USB\_Error\_Event (uint32\_t error) #####


---





---

Will be updated soon