# Restore_USB
1.  Open CMD 
2.  `diskpart`
3.  `list disk`
4.  `select disk <your_want_to_select_disk_number>`
5.  `clean`
6.  `create partition primary`
7.  `format fn=ntfs quick`
8.  `assign letter=F` => (If want to)
9.  `exit`
10.  done
