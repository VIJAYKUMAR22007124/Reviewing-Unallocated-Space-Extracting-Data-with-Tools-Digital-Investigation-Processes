# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage

```
lsblk

sudo dd if=/dev/sda of=/home/kali/disk.img bs=512

mmls ~/disk.img

sudo ls -lh disk.img

strings disk.img | less
```

## OUTPUT:
Unallocated Space Analysis and Extracted Data Report

![image](https://github.com/user-attachments/assets/507ad149-8192-41d5-9054-e7c05b4af220)

<br>

![image](https://github.com/user-attachments/assets/95676e10-24cd-4671-90ef-14ebfd147378)

<br>

![image](https://github.com/user-attachments/assets/fbd1d355-cbee-460f-824c-fac7e4471f7c)

<br>

![image](https://github.com/user-attachments/assets/d15cbcfa-4f75-4c96-9839-f3cea0a12054)



## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

