Geniatech HDStar V3 DVB-S/S2 Driver Patch
Patch para o driver do Geniatech HDStar V3, corrigindo compatibilidade com kernels Linux 5.10+ (ex.: Ubuntu 22.04, Debian 12). A principal mudança é a substituição de retornos INT por VOID em funções como ioctl, exigida pelas novas APIs do kernel.

Requisitos
Kernel Linux 5.10 ou superior
Ferramentas de compilação (make, gcc, linux-headers)
Tvheadend ou outro software DVB (opcional)
Compilação
git clone https://github.com/aleinorion/Geniatech-HDStar-V3.git
cd Geniatech-HDStar-V3
make
make install 


# Geniatech HDStar V3 DVB-S/S2 Driver Patch
Patch for the Geniatech HDStar V3 driver, fixing compatibility with Linux kernels 5.10+ (e.g., Ubuntu 22.04, Debian 12). The main change is the replacement of `INT` returns with `VOID` in functions like `ioctl`, as required by the new kernel APIs.

## Requirements
- Linux kernel 5.10 or higher
- Build tools (`make`, `gcc`, `linux-headers`)
- Tvheadend or other DVB software (optional)

## Compilation
```bash
git clone https://github.com/aleinorion/Geniatech-HDStar-V3.git
cd Geniatech-HDStar-V3
make
make install
