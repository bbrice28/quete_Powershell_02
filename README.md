# quete_Powershell_02

## historique.txt
Id     Duration CommandLine
  --     -------- -----------
   1        0.048 Get-Location
   2        0.064 get-host
   3        0.002 Set-Location -Path /
   4        0.001 get-location
   5        0.002 Set-Location -Path /users/bricebertho
   6        0.053 New-Item -Path Temp -ItemType Directory
   7        0.006 Set-Location Temp
   8        0.004 New-Item -Path Rep1 -ItemType Directory
   9        0.003 New-Item -Path Rep2 -ItemType Directory
  10        0.007 Get-ChildItem
  11        0.011 New-Item -Path file1 -ItemType File
  12        0.002 New-Item -Path file2 -ItemType File
  13        0.002 New-Item -Path file3 -ItemType File
  14        0.004 Get-ChildItem
  15        0.004 Move-Item -Path file1 -Destination Rep1
  16        0.005 get-childItem
  17        0.003 Get-ChildItem -Path Rep1
  18        0.006 Get-ChildItem -Recurse
  19        0.004 Get-ChildItem -Recurse
  20        0.003 Move-Item -Path Rep1 -Destination Rep2
  21        0.004  Get-ChildItem -recurse
  22        0.003 Remove-Item -Path file3
  23        0.003 Remove-Item Rep2 -Recurse
  24        0.024 clear
  25        0.001 set-Location ~/
  26        0.091 Set-Location -Path C:\
  27        0.000 #Une écriture possible pour la création d'un dossier
  28        0.009 New-Item -ItemType Directory -Path C:\ -Name FolderTest1
  29        0.000 #Une autre écriture possible pour la création d'un dossier
  30        0.009 New-Item -ItemType Directory -Path C:\FolderTest2
  31        0.000 #Création de fichier vide dans le dossier c:\FolderTest
  32        0.014 New-Item -ItemType File -Path C:\FolderTest1 -Name File1
  33        0.008 New-Item -ItemType File -Path C:\FolderTest1 -Name File2
  34        0.009 New-Item -ItemType File -Path C:\FolderTest1 -Name File3
  35        0.014 New-Item -ItemType File -Path C:\FolderTest1 -Name File4
  36        0.009 New-Item -ItemType File -Path C:\FolderTest1 -Name File5
  37        0.000 #Création de fichier vide dans le dossier c:\FolderTest2
  38        0.000 $Count = 6
  39        0.056 Do…
  40        0.010 Set-Location -Path C:\
  41        0.000 #Une écriture possible pour la création d'un dossier
  42        0.016 New-Item -ItemType Directory -Path C:\ -Name FolderTest1
  43        0.000 #Une autre écriture possible pour la création d'un dossier
  44        0.009 New-Item -ItemType Directory -Path C:\FolderTest2
  45        0.000 #Création de fichier vide dans le dossier c:\FolderTest
  46        0.009 New-Item -ItemType File -Path C:\FolderTest1 -Name File1
  47        0.012 New-Item -ItemType File -Path C:\FolderTest1 -Name File2
  48        0.009 New-Item -ItemType File -Path C:\FolderTest1 -Name File3
  49        0.009 New-Item -ItemType File -Path C:\FolderTest1 -Name File4
  50        0.013 New-Item -ItemType File -Path C:\FolderTest1 -Name File5
  51        0.000 #Création de fichier vide dans le dossier c:\FolderTest2
  52        0.000 $Count = 6
  53        0.025 Do…
  54        0.001 Set-Location -Path /users/bricebertho
  55        0.025 New-Item -ItemType directory -Patch / -Name FolderTest1
  56        0.002 New-Item -ItemType directory -Path / -Name FolderTest1
  57        0.020 New-Item -ItemType directory -Path /FolderTest2
  58        0.010 New-Item -ItemType directory -Path  /FolderTest2
  59        0.002 New-Item -ItemType directory -Path  / -Name FolderTest2
  60        0.009 New-Item -ItemType File -Path /FolderTest1 -Name File1
  61        0.001 cd FolderTest1
  62        0.009 New-Item -ItemType File -Path /FolderTest1 -Name File1
  63        0.010 New-Item -ItemType -Path ~/ -Name File1
  64        0.002 New-Item -ItemType File -Path ~/ -Name File1
  65        0.002 New-Item -ItemType File -Path ~/ -Name File2
  66        0.002 New-Item -ItemType File -Path ~/ -Name File3
  67        0.004 New-Item -ItemType File -Path ~/ -Name File4
  68        0.002 New-Item -ItemType File -Path ~/ -Name File5
  69        0.001 cd
  70        0.002 cd FolderTest2
  71        0.002 New-Item -ItemType File -Path ~/ -Name File6
  72        0.002 New-Item -ItemType File -Path ~/ -Name File7
  73        0.002 New-Item -ItemType File -Path ~/ -Name File8
  74        0.002 New-Item -ItemType File -Path ~/ -Name File9
  75        0.002 New-Item -ItemType File -Path ~/ -Name File10
  76        0.017 move-item -path File6 -Destination >/EvenFolder
  77        0.003 cd
  78        0.009 New-Item -ItemType Directory -Path /F
  79        0.002 New-Item -ItemType Directory -Path ~/evenFolder
  80        0.010 move-item -path File6 -Destination >~eEvenFolder
  81        0.018 move-item -path File6 -Destination >~/evenFolder
  82        0.002 cd FolderTest2
  83        0.011 move-item -path File6 -Destination >~/evenFolder
  84        0.020 move-item -path File6 -Destination evenFolder
  85        0.001 cd
  86        0.001 move-item -path File6 -Destination evenFolder
  87        0.001 move-item -path File8 -Destination evenFolder
  88        0.001 move-item -path File10 -Destination evenFolder
  89        0.001 move-item -path File4 -Destination evenFolder
  90        0.001 move-item -path File2 -Destination evenFolder
  91        0.002 New-Item -ItemType Directory -Path ~/OddFolder
  92        0.001 move-item -path File1 -Destination OddFolder
  93        0.001 move-item -path File3 -Destination OddFolder
  94        0.001 move-item -path File5 -Destination OddFolder
  95        0.001 move-item -path File7 -Destination OddFolder
  96        0.001 move-item -path File9 -Destination OddFolder




### listing.txt


  

    Directory: /Users/bricebertho

UnixMode         User Group         LastWriteTime         Size Name
--------         ---- -----         -------------         ---- ----
drwxr-xr-x briceberth staff      21/05/2024 15:29          224 evenFolder
                    o
drwxr-xr-x briceberth staff      21/05/2024 15:14           64 FolderTest1
                    o
drwxr-xr-x briceberth staff      21/05/2024 15:16           64 FolderTest2
                    o



    Directory: /Users/bricebertho

UnixMode         User Group         LastWriteTime         Size Name
--------         ---- -----         -------------         ---- ----
drwxr-xr-x briceberth staff      21/05/2024 15:30          224 OddFolder
                    o
