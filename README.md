# STM32F103_FREERTOS

```bash
git clone https://github.com/FreeRTOS/FreeRTOS ~/FreeRTOS
cd ~/FreeRTOS 
git config --global core.symlinks true
git submodule update --init --recursive
```

```bash
cp -r ~/FreeRTOS/FreeRTOS/Source $STM32WORKSPACE/MDK_ARM/FreeRTOS
```

copy FreeRTOSConfig.h From FreeRTOS/Demo

Add .h .c in Keil

Change FreeRTOS.h
