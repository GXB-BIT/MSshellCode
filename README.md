# MSshellCode
# **20251205**
<img width="1917" height="1040" alt="image" src="https://github.com/user-attachments/assets/1b1c0566-db31-4d0e-bfab-640ac1a61a30" />
将你提供的shellcode进行免杀生成exe文件

使用方法

optional arguments:

  -h, --help            show this help message and exit
  
  -i FILE, --input FILE       
              指定输入的txt文件路径
                        
  -w, --windowless            
              生成无窗口的可执行文件（去除黑色控制台）
  
  -o OUTPUT, --output OUTPUT     
              输出文件名（默认为svch0st.exe）

              
将shellcode放在与python文件同一目录下的txt文件中，shellcode要求为生成的c语言shellcode，格式如下
<img width="626" height="136" alt="image" src="https://github.com/user-attachments/assets/48f314d6-da1b-48b9-8d28-332169238778" />

<img width="1649" height="67" alt="image" src="https://github.com/user-attachments/assets/b615ac3c-9046-4750-aea7-c0d81ac21cd2" />

shellcode生成方式可以使用c2生成，例如CobaltStrike,有效载荷-payload生成器-输出格式为c语言
<img width="1920" height="507" alt="image" src="https://github.com/user-attachments/assets/984f506d-20a3-41fe-b36f-660e78fe7e8b" />
将生成后的payload.c文件使用文本编辑器打开，将shellcode内容单独复制出来即可

Vshell shellcode生成，客户端生成-shellcode-客户端类型根据目标服务器选择-格式选择c语言
<img width="1730" height="731" alt="image" src="https://github.com/user-attachments/assets/0d109214-69a8-472b-b5cd-0c35de00862f" />
同样将生成的payload.c文件使用文本编辑器打开，将shellcode内容单独复制出来即可

其他c2服务器shellcode也支持。
  
在cmd控制台输入python3 .\shellcode.py即可，需要电脑有x86_64-w64-mingw32环境，以及其他python第三方库
<img width="1096" height="248" alt="image" src="https://github.com/user-attachments/assets/fcdf7007-691e-42e9-9b03-70bbfca8c5aa" />

没有python环境或者python环境运行不起来的请下载exe格式的使用，目前exe格式生成器本身不免杀会被你电脑上的火绒或者其他杀毒软件发现，但是生成的木马exe文件是免杀的


使用方法：直接在cmd窗口执行.\MShellcode.exe即可，他会自动找到你当前文件夹中的txt文件作为shellcode进行处理，所以执行时注意当前文件夹是否存在多个txt文件

<img width="557" height="48" alt="image" src="https://github.com/user-attachments/assets/81264326-0738-44f7-b1e5-05d90a7309ea" />
<img width="821" height="520" alt="image" src="https://github.com/user-attachments/assets/abc7436e-0935-4657-a963-5923fbc68964" />
<img width="1611" height="967" alt="image" src="https://github.com/user-attachments/assets/a489ead5-2ce7-4875-8589-fe6720149f3e" />
<img width="1414" height="818" alt="image" src="https://github.com/user-attachments/assets/ed9838ed-b0f7-4c57-9a9a-f9b3b0e75726" />




