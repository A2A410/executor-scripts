# executor-scripts
executor scripts by ai&amp;j

My Executor scripts

<details>
<summary>Executor-Hooks </summary>

- This are the test hooks i created to test the executor what hooks is it compatible.

<details>
<summary>Test Hooks</summary>
[Test-Hooks](executor-hooks/test-hooks)
[Test-Hooks-Extended](executor-hooks/test-hooks-extended)

- So what it does is it tests your executor to see what hooks is compatible or possible.
- After executing this the test will start but use the script on a game with less protection to really start the test.
- If its successful, it should log it the log codes

0 - means failure
1 - success or working 
2 - exist but misconfigured means the use is quite different 
3 - available but blocked by game security

# For test hooks only the first part
Match it

[01] hookfunction  
[02] hookmetamethod  
[03] getnamecallmethod  
[04] getcallingscript  
[05] checkcaller  
[06] isexecutorclosure  
[07] identifyexecutor  
[08] rconsoleprint  
[09] rconsolewarn  
[10] rconsoleerr  
[11] rconsoleclear  
[12] gethui  
[13] syn.request  
[14] http_request  
[15] is_protosmasher_closure  
[16] getloadedmodules  
[17] getrawmetatable  
[18] debug.getmetatable  
[19] debug.getupvalue  
[20] debug.setupvalue  
[21] debug.getconstants  
[22] debug.setconstants  
[23] getgc  
[24] getupvalues  
[25] getclosure  
[26] getclosures  
[27] getreg  
[28] getsenv  
[29] getfenv  
[30] setfenv  
[31] newcclosure  
[32] writefile  
[33] readfile  
[34] delfile  
[35] setreadonly  
[36] decompile  
[37] islclosure  
[38] iscclosure  
[39] isluaclosure  
[40] clonefunction  
[41] replaceclosure  
[42] setfflag  
[43] fireclickdetector  
[44] firetouchinterest  
[45] fireproximityprompt  
[46] hook_signal  
[47] getproto  
[48] setproto  
[49] debug.traceback


# For the second part or scripts

🧠 EXECUTOR/DEBUG HOOKS

01. isexecutorclosure
02. checkcaller
03. hookfunction
04. hookmetamethod
05. newcclosure
06. getgenv
07. getrenv
08. getreg
09. getgc
10. getconnections
11. getupvalues
12. setupvalue
13. getconstants
14. setconstant
15. getinfo
16. debug.getupvalue
17. debug.setupvalue
18. debug.getinfo
19. debug.getlocal
20. debug.setlocal
21. debug.traceback

🔁 METATABLE HOOKS

22. hook __index
23. hook __newindex
24. hook __namecall
25. setreadonly
26. isreadonly

🧠 MEMORY/INTERNAL HOOKS

27. getrenv()._G
28. collectgarbage
29. rawset
30. rawget

📡 NETWORK / CLIENT-META

31. hookfunction on RemoteEvent:FireServer
32. hookfunction on RemoteFunction:InvokeServer

📊 ROBLOX PERFORMANCE STATS – CORE

33. Stats:GetTotalMemoryUsageMb()
34. Stats:GetMemoryUsageMbForTag("PhysicsParts")
35. Stats:GetDataSendKbps()
36. Stats:GetDataReceiveKbps()
37. Stats:GetServerStatsItem("Data Ping")
38. Stats:GetServerStatsItem("FPS")

🔬 ROBLOX PERFORMANCE STATS – ADVANCED

39. Stats:GetServerStatsItem("HeartbeatTimeMs")
40. Stats:GetServerStatsItem("PhysicsStepTimeMs")
41. Stats:GetServerStatsItem("MoveTimeMs")
42. Stats:GetServerStatsItem("RenderStepTimeMs")
43. Stats:GetMemoryUsageMbForTag("GraphicsTexture")
44. Stats:GetMemoryUsageMbForTag("Sounds")
45. Stats:GetMemoryUsageMbForTag("HttpCache")
46. Stats:GetMemoryUsageMbForTag("Navigation")
47. Stats:GetMemoryUsageMbForTag("Animations")
48. Stats:GetMemoryUsageMbForTag("Internal")
49. Stats:GetMemoryUsageMbForTag("CSG")

</details>

The above should suffice for now.

</details>

END
