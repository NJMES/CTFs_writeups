# Tab, Tab, Attack

#generalskills #20points

## Description

Using tabcomplete in the Terminal will add years to your life, esp. 
when dealing with long rambling directory structures and filenames: 
Addadshashanammu.zip link(https://mercury.picoctf.net/static/659efd595171e4c40378be6a2e9b7298/Addadshashanammu.zip)

hint 1: After `unzip`ing, this problem can be solved with 11 button-presses...(mostly Tab)...

process: 
    - wget https://mercury.picoctf.net/static/659efd595171e4c40378be6a2e9b7298/Addadshashanammu.zip
    - unzip Addadshashanammu.zip 
    - cd Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku/
    - dir
      - fang-of-haynekhtnamet   #this is not a folder. 
    - cat fang-of-haynekhtnamet
      - result:

H        ]fDUH]fUHH=]f.DAWAVIAUATL%F UH-F SAIL)HWHt 1LLDAHH9u[]A\A]A^A_Ðf.*ZAP!* picoCTF{l3v3l_up!_t4k3_4_r35t!_524e3dc4}X"H0zRx
                                                                                                                               Rx
                                                                                                                                 FJ
                         crtstuff.cderegister_tm_clones__do_global_dtors_auxcompleted.7698__do_global_dtors_aux_fini_array_entryframe_dummy__frame_dummy_init_array_entryfang-of-haynekhtnamet.c__FRAME_END____init_array_end_DYNAMIC__init_array_start__GNU_EH_FRAME_HDR_GLOBAL_OFFSET_TABLE___libc_csu_fini_ITM_deregisterTMCloneTableputs@@GLIBC_2.2.5_edata__libc_start_main@@GLIBC_2.2.5__data_start__gmon_start____dso_handle_IO_stdin_used__libc_csu_init__bss_startmain__TMC_END___ITM_registerTMCloneTable__cxa_finalize@@GLIBC_2.2.5.symtab.strtab.shstrtab.interp.note.ABI-tag.note.gnu.build-id.gnu.hash.dynsym.dynstr.gnu.version.gnu.version_r.rela.dyn.rela.plt.init.plt.got.text.fini.rodata.eh_frame_hdr.eh_frame.init_array.fini_array.dynamic.data.bss.comment

    - result: picoCTF{l3v3l_up!_t4k3_4_r35t!_524e3dc4}

Flag: picoCTF{l3v3l_up!_t4k3_4_r35t!_524e3dc4}