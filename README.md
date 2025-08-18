# Resources
## Content
**maybe_bootloader.bin:** psp-bootloader extraced from below bios image with [PSPTool](https://github.com/PSPReverse/PSPTool) \
**maybe_bootloader.bin.i64:** IDA database with a large amount of functions/variables labled
## BIOS Image
BIOS F66g for the Gigabyte B450 Aorus Pro board: [B450AORUSPRO.F66g](https://www.gigabyte.com/uk/Motherboard/B450-AORUS-PRO-rev-10/support#support-dl)

## Code and Resources:
**PSPReverse:**
 - Github: https://github.com/PSPReverse
 - Especially their great talks and papers (links in the readme of [PSPTool](https://github.com/PSPReverse/PSPTool))

**CoreBoot:**
 - At the [official git repo](https://review.coreboot.org/coreboot.git) or [mirror on GitHub](https://github.com/coreboot/coreboot).
 - PSP-related code can be found in [bl_syscall_public.h](https://github.com/coreboot/coreboot/blob/main/src/vendorcode/amd/psp_verstage/picasso/include/bl_uapp/bl_syscall_public.h) and other files in the parent directories

 **AMD repositories:**
 - [firmware_binaries](https://github.com/amd/firmware_binaries): Firmware binaries and error definitions
 - See especially [bl_errorcodes_public.h.txt](https://github.com/amd/firmware_binaries/blob/main/picasso/PSP/bl_errorcodes_public.h.txt) and [PspBLErrorCode.csv](https://github.com/amd/firmware_binaries/blob/main/picasso/PSP/PspBLErrorCode.csv) for Error-codes
 - [ASPFW](https://github.com/amd/AMD-ASPFW) is the (mostly complete) SEV implementation

 **Dayzerosec-blog:**
 - [Reversing the AMD Secure Processor (PSP) - Part 1: Design and Overview](https://dayzerosec.com/blog/2023/04/17/reversing-the-amd-secure-processor-psp.html)
 - [Reversing the AMD Secure Processor (PSP) - Part 2: Cryptographic Co-Processor (CCP)](https://dayzerosec.com/blog/2023/04/22/reversing-the-amd-secure-processor-psp-part-2-cryptographic-co-processor-ccp.html)

 **Linux CCP Driver:**
 - [CCP-Driver OnlineView](https://elixir.bootlin.com/linux/v5.19.17/source/drivers/crypto/ccp)

 **AMD Documents**
 - [RegisterReferenceAMD17h.pdf](https://www.amd.com/content/dam/amd/en/documents/processor-tech-docs/programmer-references/56255_OSRR.pdf)
 - [Processor Programming
Reference.pdf](https://kolegite.com/EE_library/datasheets_and_manuals/CPU/AMD_EPYC/Programming_manual_17h.pdf) 
