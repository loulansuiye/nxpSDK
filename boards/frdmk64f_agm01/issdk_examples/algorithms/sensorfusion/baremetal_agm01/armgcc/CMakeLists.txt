INCLUDE(CMakeForceCompiler)

# CROSS COMPILER SETTING
SET(CMAKE_SYSTEM_NAME Generic)
CMAKE_MINIMUM_REQUIRED (VERSION 2.6)

# THE VERSION NUMBER
SET (Tutorial_VERSION_MAJOR 1)
SET (Tutorial_VERSION_MINOR 0)

# ENABLE ASM
ENABLE_LANGUAGE(ASM)

SET(CMAKE_STATIC_LIBRARY_PREFIX)
SET(CMAKE_STATIC_LIBRARY_SUFFIX)

SET(CMAKE_EXECUTABLE_LIBRARY_PREFIX)
SET(CMAKE_EXECUTABLE_LIBRARY_SUFFIX)

 
# CURRENT DIRECTORY
SET(ProjDirPath ${CMAKE_CURRENT_SOURCE_DIR})


SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -DDEBUG")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -D__STARTUP_CLEAR_BSS")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -g")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -Wall")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -fno-common")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -ffunction-sections")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -fdata-sections")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -ffreestanding")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -fno-builtin")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -mthumb")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -mapcs")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -std=gnu99")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -mcpu=cortex-m4")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -mfloat-abi=hard")

SET(CMAKE_ASM_FLAGS_DEBUG "${CMAKE_ASM_FLAGS_DEBUG} -mfpu=fpv4-sp-d16")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -DNDEBUG")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -D__STARTUP_CLEAR_BSS")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -Wall")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -fno-common")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -ffunction-sections")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -fdata-sections")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -ffreestanding")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -fno-builtin")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -mthumb")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -mapcs")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -std=gnu99")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -mcpu=cortex-m4")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -mfloat-abi=hard")

SET(CMAKE_ASM_FLAGS_RELEASE "${CMAKE_ASM_FLAGS_RELEASE} -mfpu=fpv4-sp-d16")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -DDEBUG")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -DCPU_MK64FN1M0VLL12")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -DFRDM_K64F")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -DFREEDOM")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -DPRINTF_ADVANCED_ENABLE")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -g")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -O0")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -Wall")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -fno-common")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -ffunction-sections")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -fdata-sections")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -ffreestanding")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -fno-builtin")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -mthumb")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -mapcs")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -std=gnu99")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -mcpu=cortex-m4")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -mfloat-abi=hard")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -mfpu=fpv4-sp-d16")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -MMD")

SET(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -MP")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -DNDEBUG")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -DCPU_MK64FN1M0VLL12")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -DFRDM_K64F")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -DFREEDOM")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -DPRINTF_ADVANCED_ENABLE")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -Os")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -Wall")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -fno-common")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -ffunction-sections")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -fdata-sections")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -ffreestanding")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -fno-builtin")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -mthumb")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -mapcs")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -std=gnu99")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -mcpu=cortex-m4")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -mfloat-abi=hard")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -mfpu=fpv4-sp-d16")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -MMD")

SET(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -MP")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -DDEBUG")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -DCPU_MK64FN1M0VLL12")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -g")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -O0")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -Wall")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -fno-common")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -ffunction-sections")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -fdata-sections")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -ffreestanding")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -fno-builtin")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -mthumb")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -mapcs")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -fno-rtti")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -fno-exceptions")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -mcpu=cortex-m4")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -mfloat-abi=hard")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -mfpu=fpv4-sp-d16")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -MMD")

SET(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -MP")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -DNDEBUG")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -DCPU_MK64FN1M0VLL12")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -Os")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -Wall")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -fno-common")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -ffunction-sections")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -fdata-sections")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -ffreestanding")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -fno-builtin")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -mthumb")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -mapcs")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -fno-rtti")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -fno-exceptions")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -mcpu=cortex-m4")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -mfloat-abi=hard")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -mfpu=fpv4-sp-d16")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -MMD")

SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -MP")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -g")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} --specs=nano.specs")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} --specs=nosys.specs")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -Wall")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -fno-common")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -ffunction-sections")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -fdata-sections")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -ffreestanding")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -fno-builtin")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -mthumb")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -mapcs")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -Xlinker")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} --gc-sections")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -Xlinker")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -static")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -Xlinker")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -z")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -Xlinker")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} muldefs")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -Xlinker")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -Map=output.map")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -mcpu=cortex-m4")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -mfloat-abi=hard")

SET(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -mfpu=fpv4-sp-d16")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} --specs=nano.specs")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} --specs=nosys.specs")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -Wall")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -fno-common")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -ffunction-sections")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -fdata-sections")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -ffreestanding")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -fno-builtin")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -mthumb")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -mapcs")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -Xlinker")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} --gc-sections")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -Xlinker")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -static")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -Xlinker")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -z")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -Xlinker")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} muldefs")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -Xlinker")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -Map=output.map")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -mcpu=cortex-m4")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -mfloat-abi=hard")

SET(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -mfpu=fpv4-sp-d16")

include_directories(${ProjDirPath}/..)

include_directories(${ProjDirPath}/..)

include_directories(${ProjDirPath}/../../../../..)

include_directories(${ProjDirPath}/..)

include_directories(${ProjDirPath}/../../../../../../../CMSIS/Include)

include_directories(${ProjDirPath}/../../../../../../../devices)

include_directories(${ProjDirPath}/../../../../../../../platform/drivers)

include_directories(${ProjDirPath}/../../../../../../frdmk64f)

include_directories(${ProjDirPath}/../../../../../../../devices/MK64F12/drivers)

include_directories(${ProjDirPath}/../../../../../../../devices/MK64F12/cmsis_drivers)

include_directories(${ProjDirPath}/../../../../../../../middleware/issdk/drivers/systick)

include_directories(${ProjDirPath}/../../../../../../../middleware/issdk/drivers/gpio)

include_directories(${ProjDirPath}/../../../../../../../middleware/issdk/drivers/gpio/kinetis)

include_directories(${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources)

include_directories(${ProjDirPath}/../../../../../../../middleware/issdk/sensors)

include_directories(${ProjDirPath}/../../../../../../../devices/MK64F12/utilities/str)

include_directories(${ProjDirPath}/../../../../../../../devices/MK64F12/utilities/debug_console)

include_directories(${ProjDirPath}/../../../../../../../components/uart)

include_directories(${ProjDirPath}/../../../../../../../components/serial_manager)

include_directories(${ProjDirPath}/../../../../../../../components/lists)

include_directories(${ProjDirPath}/../../../../../../../devices/MK64F12)

include_directories(${ProjDirPath}/../../../../../../../CMSIS/Driver/Include)

include_directories(${ProjDirPath}/../../../../../../../devices/MK64F12/template)

add_executable(sensorfusion_bm_agm01.elf 
"${ProjDirPath}/../../../../../frdm_k64f.c"
"${ProjDirPath}/../../../../../frdm_k64f.h"
"${ProjDirPath}/../../../../../frdm_stbc_agm01_shield.h"
"${ProjDirPath}/../../../../../issdk_hal.h"
"${ProjDirPath}/../../../../../RTE_Device.h"
"${ProjDirPath}/../build.h"
"${ProjDirPath}/../main_baremetal.c"
"${ProjDirPath}/../pin_mux.c"
"${ProjDirPath}/../pin_mux.h"
"${ProjDirPath}/../clock_config.c"
"${ProjDirPath}/../clock_config.h"
"${ProjDirPath}/../board.c"
"${ProjDirPath}/../board.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_port.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_uart.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_uart.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_gpio.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_gpio.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_i2c.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_i2c.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_i2c_edma.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_i2c_edma.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/cmsis_drivers/fsl_i2c_cmsis.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/cmsis_drivers/fsl_i2c_cmsis.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_dmamux.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_dmamux.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_edma.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_edma.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_dspi.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_dspi.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_dspi_edma.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_dspi_edma.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/cmsis_drivers/fsl_dspi_cmsis.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/cmsis_drivers/fsl_dspi_cmsis.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_ftfx_adapter.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_ftfx_utilities.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_ftfx_features.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_ftfx_controller.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_ftfx_controller.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_ftfx_flash.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_ftfx_flash.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_ftfx_cache.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_ftfx_cache.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_ftfx_flexnvm.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_ftfx_flexnvm.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_flash.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_smc.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_smc.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_pit.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_pit.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_uart_edma.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_uart_edma.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/cmsis_drivers/fsl_uart_cmsis.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/cmsis_drivers/fsl_uart_cmsis.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/drivers/systick/systick_utils.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/drivers/systick/systick_utils.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/drivers/gpio/kinetis/gpio_driver_irq.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/drivers/gpio/kinetis/gpio_driver.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/drivers/gpio/kinetis/gpio_driver.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/drivers/gpio/Driver_GPIO.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/approximations.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/approximations.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/calibration_storage.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/calibration_storage.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/control.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/control.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/debug.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/debug.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/DecodeCommandBytes.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/driver_FXAS21002.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/driver_FXOS8700.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/driver_MPL3115.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/driver_KSDK_NVM.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/driver_KSDK_NVM.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/driver_pit.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/driver_pit.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/driver_systick.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/drivers.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/fusion.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/fusion.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/hal_frdm_fxs_mult2_b.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/magnetic.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/magnetic.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/matrix.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/matrix.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/orientation.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/orientation.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/output_stream.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/precisionAccelerometer.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/precisionAccelerometer.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/sensor_fusion.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/sensor_fusion.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/status.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/algorithms/sensorfusion/sources/status.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/register_io_i2c.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/register_io_spi.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/sensor_io_spi.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/sensor_io_i2c.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/register_io_i2c.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/register_io_spi.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/sensor_io_spi.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/sensor_io_i2c.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/sensor_drv.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/fxas21002.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/fxas21002_drv.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/fxas21002_drv.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/fxos8700.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/fxos8700_drv.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/fxos8700_drv.c"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/mpl3115.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/mpl3115_drv.h"
"${ProjDirPath}/../../../../../../../middleware/issdk/sensors/mpl3115_drv.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_clock.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_clock.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/utilities/str/fsl_str.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/utilities/str/fsl_str.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/utilities/debug_console/fsl_debug_console.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/utilities/debug_console/fsl_debug_console.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/utilities/debug_console/fsl_debug_console_conf.h"
"${ProjDirPath}/../../../../../../../components/uart/uart.h"
"${ProjDirPath}/../../../../../../../components/uart/uart_adapter.c"
"${ProjDirPath}/../../../../../../../components/serial_manager/serial_manager.h"
"${ProjDirPath}/../../../../../../../components/serial_manager/serial_manager.c"
"${ProjDirPath}/../../../../../../../components/serial_manager/serial_port_uart.h"
"${ProjDirPath}/../../../../../../../components/serial_manager/serial_port_uart.c"
"${ProjDirPath}/../../../../../../../components/lists/generic_list.h"
"${ProjDirPath}/../../../../../../../components/lists/generic_list.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/fsl_device_registers.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/MK64F12.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/MK64F12_features.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/system_MK64F12.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/system_MK64F12.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_common.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/drivers/fsl_common.c"
"${ProjDirPath}/../../../../../../../devices/MK64F12/gcc/startup_MK64F12.S"
"${ProjDirPath}/../../../../../../../devices/MK64F12/utilities/fsl_assert.c"
"${ProjDirPath}/../../../../../../../CMSIS/Include/core_cm4.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/cmsis_armcc.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/cmsis_armclang.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/cmsis_gcc.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/cmsis_compiler.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/cmsis_version.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/mpu_armv7.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/core_armv8mbl.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/core_armv8mml.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/arm_common_tables.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/arm_const_structs.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/arm_math.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/cmsis_iccarm.h"
"${ProjDirPath}/../../../../../../../CMSIS/Include/mpu_armv8.h"
"${ProjDirPath}/../../../../../../../CMSIS/Driver/Include/Driver_I2C.h"
"${ProjDirPath}/../../../../../../../CMSIS/Driver/Include/Driver_Common.h"
"${ProjDirPath}/../../../../../../../devices/MK64F12/template/RTE_Device.h"
"${ProjDirPath}/../../../../../../../CMSIS/Driver/Include/Driver_SPI.h"
"${ProjDirPath}/../../../../../../../CMSIS/Driver/Include/Driver_USART.h"
)


set(CMAKE_EXE_LINKER_FLAGS_DEBUG "${CMAKE_EXE_LINKER_FLAGS_DEBUG} -T${ProjDirPath}/MK64FN1M0xxx12_flash.ld -static")

set(CMAKE_EXE_LINKER_FLAGS_RELEASE "${CMAKE_EXE_LINKER_FLAGS_RELEASE} -T${ProjDirPath}/MK64FN1M0xxx12_flash.ld -static")

TARGET_LINK_LIBRARIES(sensorfusion_bm_agm01.elf -Wl,--start-group)
target_link_libraries(sensorfusion_bm_agm01.elf debug m)

target_link_libraries(sensorfusion_bm_agm01.elf debug c)

target_link_libraries(sensorfusion_bm_agm01.elf debug gcc)

target_link_libraries(sensorfusion_bm_agm01.elf debug nosys)

target_link_libraries(sensorfusion_bm_agm01.elf optimized m)

target_link_libraries(sensorfusion_bm_agm01.elf optimized c)

target_link_libraries(sensorfusion_bm_agm01.elf optimized gcc)

target_link_libraries(sensorfusion_bm_agm01.elf optimized nosys)

TARGET_LINK_LIBRARIES(sensorfusion_bm_agm01.elf -Wl,--end-group)

ADD_CUSTOM_COMMAND(TARGET sensorfusion_bm_agm01.elf POST_BUILD COMMAND ${CMAKE_OBJCOPY}
-Obinary ${EXECUTABLE_OUTPUT_PATH}/sensorfusion_bm_agm01.elf ${EXECUTABLE_OUTPUT_PATH}/K64F-AGM01-SENSORFUSION-BAREMETAL.bin)
