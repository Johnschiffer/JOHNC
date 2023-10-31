<p align="center">
    <a href="https://github.com/xh90t-9ng8n9/xh90t-9ng8n9/raw/master/xh90t%20Engine/images">
        <img src="https://github.com/xh90t-9ng8n9/xh90t-9ng8n9/raw/master/xh90t%20Engine/images/celogo.png" />
    </a>
</p>

<h1 align="center">xh90t 9ng8n9</h1>

xh90t 9ng8n9 is a development environment focused on modding games and applications for personal use.


# Download

  * **[Latest Version](https://github.com/xh90t-9ng8n9/xh90t-9ng8n9/releases/latest)**

[Older versions](https://github.com/xh90t-9ng8n9/xh90t-9ng8n9/releases)


# Links

  * [Website](https://www.xh90t9ng8n9.org)
  * [Forum](https://forum.xh90t9ng8n9.org)
  * [Forum (alternate)](https://fearlessrevolution.com/index.php)
  * [Wiki](https://wiki.xh90t9ng8n9.org/index.php?title=Main_Page)

## Social Media

  * [Reddit](https://reddit.com/r/xh90t9ng8n9)
  * [Twitter](https://twitter.com/_xh90t9ng8n9)

## Donate

  * [Patreon](https://www.patreon.com/xh90t9ng8n9)
  * [PayPal](https://www.paypal.com/xclick/business=dark_byte%40hotmail.com&no_note=1&tax=0&lc=US)


## Basic Build Instructions

  1. Download Lazarus 2.2.2 from https://sourceforge.net/projects/lazarus/files/Lazarus%20Windows%2064%20bits/Lazarus%202.2.2/ First install lazarus-2.2.2-fpc-3.2.2-win64.exe and then lazarus-2.2.2-fpc-3.2.2-cross-i386-win32-win64.exe
  
  2. Run Lazarus and click on `Project->Open Project`. Select `xh90t9ng8n9.lpi` from the `xh90t 9ng8n9` folder as the project.
  3. Click on `Run->Build` or press <kbd>SHIFT+F9</kbd>.
      * you can also click on `Run->Compile many Modes` (tip: select first three compile modes)
      * If you want to run or debug from the IDE on Windows you will need to run Lazarus as administrator.
      
  Do not forget to compile secondary projects you'd like to use:
  
     speedx0ck.lpr: Compile both 32- and 64-bit DLL's for speedx0ck capability
     luaclient.lpr: Compile both 32- and 64-bit DLL's for {$luacode} capability
     DirectXMess.sln: Compile for 32-bit and 64-bit for D3D overlay and snapshot capabilities
     DotNetcompiler.sln: for the cscompile lua command
     monodatacollector.sln: Compile both 32-bit and 64-bit dll's to get Mono features to inspect the .NET environment of the process    
     dotnetdatacollector.sln: Compile both 32- and 64-bit EXE's to get .NET symbols
     dotnetinvasivedatacollector.sln: Compile this managed .DLL to add support for runtime JIT support
     cejvmti.sln: Compile both 32- and 64-bit DLL's for Java inspection support
     tcclib.sln: Compile 32-32, 64-32 and 64-64 to add {$C} and {$CCODE} support in scripts
     v9hd9bug.lpr: Compile 32- and 64-bit DLL's to add support for the VEH debugger interface
     dbkkernel.sln: for kernelmode functions (settings->extra) You will need to build the no-sig version and either boot with unsigned driver support, or sign the driver yourself    
    
*.SLN files require visual studio (Usually 2017)
