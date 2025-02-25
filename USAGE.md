# Usage Guide

## Requirements
- **Proteus 8** or a newer version (Older versions are not supported).

## Linking the HEX File
 **Attach the HEX File to the ROM:**  
 - Make sure to link the file with the `.HEX` extension to the ROM component in Proteus.  

 **Modify Stored Data:**  
 - You can update or modify the stored data by editing the contents of the `.HEX` file manually.  

## Opcodes
| Opcode | Instruction |
|--------|-------------|
| `0000` | **LOAD**    |
| `0001` | **ADD**     | 
| `0010` | **SUP**     | 
| `1110` | **OUT**     | 
| `1111` | **HLT**     | 

## Instruction Format  
The instructions follow this binary format:
- **Opcode**: Specifies the operation to perform (4 bits).  
- **Address**: Specifies the memory location (4 bits).  

After linking the `.HEX` file and understanding the opcodes, your SAP-1 simulation should run smoothly.












            

