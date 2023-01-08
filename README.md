<html>
<head>
<title>README Files</title>
</head>
<body background="backgd.gif">
<hr><hr>
<table width ="100%">
  <tr align="center" bgcolor="#e4e4e4">
    <td>
      <h1><big><font color="#3c34ec"><i>NuttX README Files</i></font></big></h1>
      <p>Last Updated:  May 26, 2016</p>
    </td>
  </tr>
</table>
<p>
  Additional information can be found in the <code>Documentation/</code> directory and
  also in <code>README</code> files that are scattered throughout the source tree.
  Below is a guide to the available <code>README</code> files.
  Some <code>README</code> files contain more important information than others.
  The key <code>README</code> files are shown in <code><i><b>BOLDFACE/ITALIC</i></b></code> below.
</p>
<p>
  Below is a guide to the available README files in the NuttX source tree:
</p>

<ul><pre>
nuttx/
 |- <a href="https://bitbucket.org/nuttx/nuttx/src/master/README.txt" target="_blank"><b>README.txt</b></a>
 |- arch/
 |   |
 |   |- arm/
 |   |   `- src
 |   |       `- <a href="https://bitbucket.org/nuttx/nuttx/arch/src/master/arm/src/lpc214x/README.txt" target="_blank">lpc214x/README.txt</a>
 |   |- sh/
 |   |   |- include/
 |   |   |   `-<a href="https://bitbucket.org/nuttx/nuttx/arch/src/master/sh/include/README.txt" target="_blank">README.txt</a>
 |   |   |- src/
 |   |   |   `-<a href="https://bitbucket.org/nuttx/nuttx/arch/src/master/sh/src/README.txt" target="_blank">README.txt</a>
 |   |- x86/
 |   |   |- include/
 |   |   |   `-<a href="https://bitbucket.org/nuttx/nuttx/arch/src/master/x86/include/README.txt" target="_blank">README.txt</a>
 |   |   `- src/
 |   |       `-<a href="https://bitbucket.org/nuttx/nuttx/arch/src/master/x86/src/README.txt" target="_blank">README.txt</a>
 |   |- z80/
 |   |   |- src/z80
 |   |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/arch/src/master/z80/src/z80/README.txt" target="_blank">README.txt</a>
 |   |   `- src/z180
 |   |       |- <a href="https://bitbucket.org/nuttx/nuttx/arch/src/master/z80/src/z180/README.txt" target="_blank">README.txt</a>
 |   |       `- <a href="https://bitbucket.org/nuttx/nuttx/arch/src/master/z80/src/z180/z180_mmu.txt" target="_blank">z180_mmu.txt</a>
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/arch/src/master/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- binfmt/
 |   |- libpcode/
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/binfmt/libpcode/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- audio/
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/audio/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- configs/
 |   |- amber/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/amber/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- arduino-mega2560/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/arduino-mega2560/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- arduino-due/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/arduino-due/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- avr32dev1/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/avr32dev1/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- c5471evm/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/c5471evm/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- cc3200-launchpad/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/cc3200-launchpad/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- cloudctrl/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/cloudctrl/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- compal_e86/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/compal_e86/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- compal_e88/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/compal_e88/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- compal_e99/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/compal_e99/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- demo9s12ne64/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/demo9s12ne64/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- dk-tm4c129x/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/dk-tm4c129x/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- ea3131/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ea3131/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- ea3152/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ea3152/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- eagle100/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/eagle100/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- efm32-g8xx-stk/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/efm32-g8xx-stk/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- efm32gg-stk3700/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/efm32gg-stk3700/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- ekk-lm3s9b96/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ekk-lm3s9b96/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- ez80f910200kitg/
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ez80f910200kitg/ostest/README.txt" target="_blank">ostest/README.txt</a>
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ez80f910200kitg/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- ez80f910200zco/
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ez80f910200zco/ostest/README.txt" target="_blank">dhcpd/README.txt</a>
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ez80f910200zco/httpd/README.txt" target="_blank">httpd/README.txt</a>
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ez80f910200zco/nettest/README.txt" target="_blank">nettest/README.txt</a>
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ez80f910200zco/nsh/README.txt" target="_blank">nsh/README.txt</a>
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ez80f910200zco/ostest/README.txt" target="_blank">ostest/README.txt</a>
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ez80f910200zco/poll/README.txt" target="_blank">poll/README.txt</a>
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ez80f910200zco/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- fire-stm32v2/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/fire-stm32v2/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- freedom-kl25z/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/freedom-kl25z/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- freedom-kl26z/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/freedom-kl26z/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- hymini-stm32v/
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/hymini-stm32v/RIDE/README.txt" target="_blank">RIDE/README.txt</a>
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/hymini-stm32v/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- kwikstik-k40/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/kwikstik-k40/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- launchxl-tms57004/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/launchxl-tms57004/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- lincoln60/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/lincoln60/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- lm3s6432-s2e/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/lm3s6432-s2e/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- lm3s6965-ek/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/lm3s6965-ek/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- lm3s8962-ek/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/lm3s8962-ek/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- lpc4330-xplorer/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/llpc4330-xplorer/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- lpc4337-ws/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/llpc4337-ws/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- lpc4357-evb/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/llpc4357-evb/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- lpc4370-link2/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/llpc4370-link2/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- lpcxpresso-lpc1115/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/lpcxpresso-lpc1115/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- lpcxpresso-lpc1768/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/lpcxpresso-lpc1768/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- maple/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/maple/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- mbed/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/mbed/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- mcu123-lpc214x/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/mcu123-lpc214x/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- micropendous3/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/micropendous3/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- mikroe-stm32f4/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/mikroe-stm32f4/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- mirtoo/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/mirtoo/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- mt-db-x3//
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/mt-db-x3//README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- moteino-mega/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/moteino-mega/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- mx1ads/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/mx1ads/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- ne64badge/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ne64badge/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- ntosd-dm320/
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ntosd-dm320/doc/README.txt" target="_blank">doc/README.txt</a>
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ntosd-dm320/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- nucleo-144/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/nucleo-144/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- nucleo-f4x1re/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/nucleo-f4x1re/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- nutiny-nuc120/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/nutiny-nuc120/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- olimex-efm32g880f129-stk/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/olimex-efm32g880f129-stk/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- olimex-lpc1766stk/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/olimex-lpc1766stk/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- olimex-lpc2378/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/olimex-lpc2378/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- olimex-lpc-h3131/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/olimex-lpc-h3131/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- olimex-stm32-h405/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/olimex-stm32-h405/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- olimex-stm32-h407/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/olimex-stm32-h407/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- olimex-stm32-p107/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/olimex-stm32-p107/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- olimex-stm32-p207/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/olimex-stm32-p207/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- olimex-strp711/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/olimex-strp711/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- open1788/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/open1788/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- p112/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/p112/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- pcblogic-pic32mx/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/pcblogic-pic32mx/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- pcduino-a10/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/pcduino-pic32mx/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- pic32mx-starterkit/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/pic32mx-starterkit/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- pic32mx7mmb/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/pic32mx7mmb/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- pic32mz-starterkit/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/pic32mz-starterkit/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- pirelli_dpl10/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/pirelli_dpl10/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- qemu-i486/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/qemu-i486/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- rgmp/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/rgmp/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sabre-6quad/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sabre-6quad/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sama5d2-xult/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sama5d2-xult/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sama5d3x-ek/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sama5d3x-ek/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sama5d3-xplained/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sama5d3-xplained/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sama5d4-ek/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sama5d4-ek/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- samd20-xplained/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/samd20-xplained/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- samd21-xplained/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/samd21-xplained/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- saml21-xplained/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/saml21-xplained/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sam3u-ek/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sam3u-ek/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sam4e-ek/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sam4e-ek/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sam4l-xplained/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sam4l-xplained/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sam4s-xplained/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sam4s-xplained/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sam4s-xplained-pro/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sam4s-xplained-pro/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- same70-xplained/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/same70-xplained/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- samv71-xult/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/samv71-xult/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- shenzhou/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/shenzhou/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sim/
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sim/include/README.txt" target="_blank"><b><i>include/README.txt</i></b></a>
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sim/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- skp16c26/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/skp16c26/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- spark/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/spark/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm3210e-eval/
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm3210e-eval/RIDE/README.txt" target="_blank">RIDE/README.txt</a>
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm3210e-eval/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm3220g-eval/
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm3220g-eval/ide/nsh/uvision/README.txt" target="_blank"><b><i>ide/nsh/uvision/README.txt</i></b></a>
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm3220g-eval/ide/nsh/iar/README.txt" target="_blank"><b><i>ide/nsh/iar/README.txt</i></b></a>
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm3220g-eval/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm3240g-eval/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm3240g-eval/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm32_tiny/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm32_tiny/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm32f103-minumum/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm32f103-minumum/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm32f3discovery/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm32f3discovery/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm32f4discovery/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm32f4discovery/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm32f411e-disco/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm32f411e-disco/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm32f429i-disco/
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm32f429i-disco/ide/ltcd/uvision/README.txt" target="_blank"><b><i>ide/ltcd/uvision/README.txt</i></b></a>
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm32f429i-disco/ltdc/README.txt" target="_blank"><b><i>ltdc/README.txt</i></b></a>
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm32f429i-disco/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm32f746g-disco/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm32f746g-disco/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm32l476vg-disco/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm32l476vg-disco/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm32ldiscovery/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm32ldiscovery/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- stm32vldiscovery/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/stm32vldiscovery/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sure-pic32mx/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/sure-pic32mx/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- teensy-2.0/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/teensy-2.0/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- teensy-3.1/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/teensy-3.1/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- teensy-lc/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/teensy-lc/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- tm4c123g-launchpad/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/tm4c123g-launchpad/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- tm4c1294-launchpad/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/tm4c1294-launchpad/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- twr-k60n512/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/twr-k60n512/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- "u-blox-c027/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/u-blox-c027/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- ubw32/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/ubw32/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- us7032evb1/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/us7032evb1/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- viewtool-stm32f107/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/viewtool-stm32f107/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- xtrs/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/xtrs/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- z16f2800100zcog/
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/xtrs/ostest/README.txt" target="_blank">ostest/README.txt</a>
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/xtrs/pashello/README.txt" target="_blank">pashello/README.txt</a>
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/xtrs/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- z80sim/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/z80sim/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- z8encore000zco/
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/z8encore000zco/ostest/README.txt" target="_blank">ostest/README.txt</a>
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/z8encore000zco/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- z8f64200100kit/
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/z8f64200100kit/ostest/README.txt" target="_blank">ostest/README.txt</a>
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/z8f64200100kit/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- zkit-arm-1769/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/zkit-arm-1769/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- zp214xpa/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/zp214xpa/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/configs/src/master/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- drivers/
 |   |- eeprom/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/drivers/eeprom/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- lcd/
 |   |   |- <a href="https://bitbucket.org/nuttx/nuttx/src/master/drivers/lcd/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/drivers/lcd/pcf8574_lcd_backpack_readme.txt" target="_blank"><b><i>pcf8574_lcd_backpack_readme.txt</i></b></a>
 |   |- mtd/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/drivers/mtd/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- sensors/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/drivers/sensors/README.txt" target="_blank">README.txt</a>
 |   |- sercomm/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/drivers/sercomm/README.txt" target="_blank">README.txt</a>
 |   |- syslog/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/drivers/syslog/README.txt" target="_blank">README.txt</a>
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/drivers/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- fs/
 |   |- binfs/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/fs/binfs/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- mmap/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/fs/mmap/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- nxffs/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/fs/nxffs/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- smartfs/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/fs/smartfs/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   |- procfs/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/fs/procfs/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   `- unionfs/
 |       `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/fs/unionfs/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- graphics/
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/graphics/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- lib/
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/lib/README.txt" target="_blank">README.txt</a>
 |- libc/
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/libc/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- libnx/
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/libnx/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- libxx/
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/libxx/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- mm/
 |   |- shm/
 |   |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/mm/shm/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/mm/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- net/
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/net/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- syscall/
 |   `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/syscall/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 `- tools/
     `- <a href="https://bitbucket.org/nuttx/nuttx/src/master/tools/README.txt" target="_blank"><b><i>README.txt</i></b></a>
</pre></ul>

<p>
  Below is a guide to the available README files in the semi-optional <code>apps/</code> source tree:
</p>

<ul><pre>
apps/
 |- <a href="https://bitbucket.org/nuttx/apps/src/master/README.txt" target="_blank"><b>README.txt</b></a>
 |- examples/
 |   |- <a href="https://bitbucket.org/nuttx/apps/src/master/examples/bastest/README.txt" target="_blank">bastest/README.txt</a>
 |   |- <a href="https://bitbucket.org/nuttx/apps/src/master/examples/json/README.txt" target="_blank">json/README.txt</a>
 |   |- <a href="https://bitbucket.org/nuttx/apps/src/master/examples/pashello/README.txt" target="_blank">pashello/README.txt</a>
 |   `- <a href="https://bitbucket.org/nuttx/apps/src/master/examples/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- gpsutils/
 |   `- <a href="https://bitbucket.org/nuttx/apps/src/master/gpsutils/minmea/README.txt" target="_blank">"<b><i>minmea/README.txt</i></b></a>
 |- graphics/
 |   `- <a href="https://bitbucket.org/nuttx/apps/src/master/graphics/tiff/README.txt" target="_blank">"<b><i>tiff/README.txt</i></b></a>
 |- interpreters/
 |   |- <a href="https://bitbucket.org/nuttx/apps/src/master/interpreters/bas/README.txt" target="_blank"><b><i>bas/README.txt</i></b></a>
 |   |- <a href="https://bitbucket.org/nuttx/apps/src/master/interpreters/ficl/README.txt" target="_blank"><b><i>ficl/README.txt</i></b></a>
 |   `- <a href="https://bitbucket.org/nuttx/apps/src/master/interpreters/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- modbus/
 |   `- <a href="https://bitbucket.org/nuttx/apps/src/master/modbus/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- netutils/
 |   |   |- <a href="https://bitbucket.org/nuttx/apps/src/master/netutils/discover/README.txt" target="_blank">discover/README.txt</a>
 |   |   |- <a href="https://bitbucket.org/nuttx/apps/src/master/netutils/ftpc/README.txt" target="_blank">ftpc/README.txt</a>
 |   |   |- <a href="https://bitbucket.org/nuttx/apps/src/master/netutils/json/README.txt" target="_blank">json/README.txt</a>
 |   |   |- <a href="https://bitbucket.org/nuttx/apps/src/master/netutils/telnetd/README.txt" target="_blank">telnetd/README.txt</a>
 |   `- <a href="https://bitbucket.org/nuttx/apps/src/master/netutils/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- nshlib/
 |   `- <a href="https://bitbucket.org/nuttx/apps/src/master/nshlib/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- NxWidgets/
 |   `- <a href="https://bitbucket.org/nuttx/apps/src/master/NxWidgets/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 `- system/
     |- <a href="https://bitbucket.org/nuttx/apps/src/master/system/cdcacm/README.txt" target="_blank"><b><i>cdcacm/README.txt</i></b></a>
     |- <a href="https://bitbucket.org/nuttx/apps/src/master/system/i2c/README.txt" target="_blank"><b><i>i2c/README.txt</i></b></a>
     |- <a href="https://bitbucket.org/nuttx/apps/src/master/system/inifile/README.txt" target="_blank">inifile/README.txt</a>
     |- <a href="https://bitbucket.org/nuttx/apps/src/master/system/install/README.txt" target="_blank">install/README.txt</a>
     |- <a href="https://bitbucket.org/nuttx/apps/src/master/system/nxplayer/README.txt" target="_blank"><b><i>nxplayer/README.txt</i></b></a>
     |- <a href="https://bitbucket.org/nuttx/apps/src/master/system/symtab/README.txt" target="_blank"><b><i>symtab/README.txt</i></b></a>
     |- <a href="https://bitbucket.org/nuttx/apps/src/master/system/usbmsc/README.txt" target="_blank">usbmsc/README.txt</a>
     |- <a href="https://bitbucket.org/nuttx/apps/src/master/system/zmodem/README.txt" target="_blank">zmodem/README.txt</a>
     `- <a href="https://bitbucket.org/nuttx/apps/src/master/system/zoneinfo/README.txt" target="_blank">zoneinfo/README.txt</a>
</pre></ul>

<p>
  Additional README.txt files in the other, related repositories:
</p>

<ul><pre>
NxWidgets
 |- Doxygen
 |   `- <a href="https://bitbucket.org/nuttx/nxwidgets/src/master/Doxygen/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- tools
 |   `- <a href="https://bitbucket.org/nuttx/nxwidgets/src/master/tools/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 |- UnitTests
 |   `- <a href="https://bitbucket.org/nuttx/nxwidgets/src/master/UnitTests/README.txt" target="_blank"><b><i>README.txt</i></b></a>
 `- <a href="https://bitbucket.org/nuttx/nxwidgets/src/master/README.txt" target="_blank"><b><i>README.txt</i></b></a>

buildroot/
 `- <a href="https://bitbucket.org/nuttx/buildroot/src/master/README.txt" target="_blank"><b><i>README.txt</i></b></a>

tools/
 `- <a href="https://bitbucket.org/nuttx/tools/src/master/README.txt" target="_blank"><b><i>README.txt</i></b></a>

uClibc++/
 `- <a href="https://bitbucket.org/nuttx/uclibc/src/master/README.txt" target="_blank"><b><i>README.txt</i></b></a>

pascal/
 `- <a href="https://bitbucket.org/nuttx/pascal/src/master/README" target="_blank"><b><i>README</i></b></a>

</pre></ul>
</body>
</html>
