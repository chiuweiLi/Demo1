# Demo1

2018/3/18
asp.net core 2.0 CRUD
not connect DB


Get-ChildItem -Path "HKLM:\SOFTWARE\Microsoft\NET Framework Setup\NDP\v4\Full\" | Get-ItemProperty -Name Release | Select-Object -Property Release, @{Name="Version";Expression={switch($_.Release){460798{"4.7 (Creator's Update)"};461308{"4.7.1"};461808{"4.7.2"};528040{"4.8"};528049{"4.8.0"};533320{"4.8.1"};Default{"Unknown_or_Earlier_version"}}}}
