- in lots of forums its written to use NtWow64QueryInformationProcess64 for x64 but turn out NtWow64QueryInformationProcess64 is not anymore and NtQueryInformationProcess() works for both 32 and 64 bit architecture.
In 64 bit u have to declare a new PROCESS_BASIC_INFORMATION64 struct and pass its pointer in the ntquery func
- 📫 How to reach me ... @discord: unknownJoker49#3322  

<!---
D3AtHAdD3r/D3AtHAdD3r is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
