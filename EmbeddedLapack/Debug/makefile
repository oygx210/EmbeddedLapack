################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include src/qpOASES/Source/subdir.mk
-include src/LinearAlgebra/subdir.mk
-include src/Lapack/Scr/subdir.mk
-include src/Lapack/Install/subdir.mk
-include src/Lapack/F2c/subdir.mk
-include src/Lapack/Blas/subdir.mk
-include src/subdir.mk
-include subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: EmbeddedLapack

# Tool invocations
EmbeddedLapack: $(OBJS) $(USER_OBJS)
	@echo 'Building target: $@'
	@echo 'Invoking: GCC C Linker'
	gcc  -o "EmbeddedLapack" $(OBJS) $(USER_OBJS) $(LIBS)
	@echo 'Finished building target: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(EXECUTABLES)$(OBJS)$(C_DEPS) EmbeddedLapack
	-@echo ' '

.PHONY: all clean dependents

-include ../makefile.targets
