#Notes on CS 385

###8/25/2016
 * boot 
    + on powerup the machine is running 16 bit real mode
    + BIOS interrupts
        - small service routines
            int $0x10;  
            mov 1,al;    
            mov 0x10, ah;    
    + steps during boot 
        * read some more program from disk(into memory)
        * switch out of 16_bit mode
        * start running from beginning of the new program

> grep
>



> 获取管理员权限



