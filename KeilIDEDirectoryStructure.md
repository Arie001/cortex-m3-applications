# Description about this wiki #

The wiki is series of images followed by a text based tree structure to show the setup of keil IDE for development on LandTiger.


---

![https://lh4.googleusercontent.com/-ZovPWHws8sM/Ub8xghDXYAI/AAAAAAAAA3o/Av1nNbPZRS8/w208-h512-no/close_up_directory_structure.jpg](https://lh4.googleusercontent.com/-ZovPWHws8sM/Ub8xghDXYAI/AAAAAAAAA3o/Av1nNbPZRS8/w208-h512-no/close_up_directory_structure.jpg)

---

![https://lh5.googleusercontent.com/-YdSKpPAPL-g/Ub8xhyLnT2I/AAAAAAAAA3w/cdWguTGVv-E/w208-h512-no/excluded_from_build.jpg](https://lh5.googleusercontent.com/-YdSKpPAPL-g/Ub8xhyLnT2I/AAAAAAAAA3w/cdWguTGVv-E/w208-h512-no/excluded_from_build.jpg)

---

![https://lh6.googleusercontent.com/-24RvEqyktcE/Ub8xl5wU2OI/AAAAAAAAA34/kpA-RWBjecM/w1044-h483-no/keil_ide_directory.jpg](https://lh6.googleusercontent.com/-24RvEqyktcE/Ub8xl5wU2OI/AAAAAAAAA34/kpA-RWBjecM/w1044-h483-no/keil_ide_directory.jpg)

---

![https://lh3.googleusercontent.com/-0n5O3FJin9U/Ub8xnNnrJOI/AAAAAAAAA4A/bOzKA_QHDAY/w216-h374-no/project_tree.jpg](https://lh3.googleusercontent.com/-0n5O3FJin9U/Ub8xnNnrJOI/AAAAAAAAA4A/bOzKA_QHDAY/w216-h374-no/project_tree.jpg)

---


# Tree Structure #
```
LandTiger_ucgui_samples
|-User
|	|-main.c
|	|-uctsk_Task.c
|	|-app_cfg
|	|-includes.h
|-TouchPanel
| 	|-TouchPanel.c
|-CMSIS
| 	|-core_cm3.c
| 	|-system_LPC17xx.c
|-Startup
| 	|-startup_LPC17xx.s
|-uC-OS-II/Port
| 	|-os_cpu.h
| 	|-os_cpu_c.c
| 	|-os_cpu_a.asm
| 	|-os_dbg.c
|-uC-OS-II/Source
| 	|-os_core.c
| 	|-os_flag.c
| 	|-os_mbox.c
| 	|-os_mem.c
| 	|-os_mutex.c
| 	|-os_q.c
| 	|-os_sem.c
| 	|-os_task.c
| 	|-os_time.c
| 	|-os_tmr.c
|-uC-OS-II/Config
| 	|-Os_AppHooks.c
| 	|-os_cfg.h
|-uCOS-?/GUI_X
| 	|-GUI_X_Touch.c
| 	|-GUI_X_uCOS.c
|-uCGUI/GLCD
| 	|-GLCD.c
| 	|-GLCD_UCGUI.c
|-uCGUI/Config
| 	|-GUIConf.h
| 	|-GUITouchConf.h
| 	|-LCDConf.h
|-uCGUI/Lib
| 	|-uCGUI.lib
|-Doc
|-glcd_driver
| 	|-GLCD_driver.c
| 	|-GLCD_driver_LPC1700.c
|-Samples
| 	|-MainTask.c
| 	|-Touch_Start.c
| 	|-button.c
| 	|-checkbox.c
| 	|-dropbox.c
```

---
