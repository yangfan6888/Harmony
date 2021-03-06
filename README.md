<p align="center">
	<img src="https://raw.githubusercontent.com/pardeike/Harmony/master/HarmonyLogo.png" alt="Harmony" width="128" />
</p>

<hr>

<p align="center">
	<a href="../../releases/latest">
		<img src="https://img.shields.io/github/release/pardeike/harmony.svg?style=flat" />
	</a>
	<a href="https://www.nuget.org/packages/lib.harmony">
		<img src="https://img.shields.io/nuget/v/lib.harmony.svg?style=flat" />
	</a>
	<a href="https://harmony.pardeike.net">
		<img src="https://img.shields.io/badge/documentation-%F0%9F%94%8D-blue?style=flat" />
	</a>
	<a href="../../blob/master/LICENSE">
		<img src="https://img.shields.io/github/license/pardeike/harmony.svg?style=flat" />
	</a>
</p>
<p align="center">
	<a href="https://dev.azure.com/pardeike/Harmony/_build">
		<img src="https://pardeike.visualstudio.com/Harmony/_apis/build/status/Build%20and%20test" />
	</a>
	<a href="https://travis-ci.org/pardeike/Harmony">
		<img src="https://img.shields.io/travis/pardeike/Harmony/master.svg?logo=travis&label=travis:master" /> 
	</a>
	<a href="https://ci.appveyor.com/project/pardeike/harmony">
		<img src="https://img.shields.io/appveyor/ci/pardeike/Harmony/master.svg?logo=appveyor&label=appveyor:master" /> 
	</a>
</p>
<p align="center">
	<a href="mailto:andreas@pardeike.net">
		<img src="https://img.shields.io/badge/email-andreas@pardeike.net-blue.svg?style=flat" />
	</a>
	<a href="https://twitter.com/pardeike">
		<img src="https://img.shields.io/badge/twitter-@pardeike-blue.svg?style=flat&logo=twitter" />
	</a>
	<a href="https://discord.gg/xXgghXR">
		<img src="https://img.shields.io/discord/131466550938042369.svg?style=flat&logo=discord&label=discord" />
	</a>
</p>

<p align="center">
	A library for patching, replacing and decorating .NET and Mono methods during runtime.
</p>

<hr>

Harmony gives you an elegant and high level way to alter the functionality in applications written in C#. It works great in games and is in fact well established in games like  
- Rimworld
- BattleTech
- Oxygen Not Included
- Subnautica
- 7 Days To Die
- Cities: Skylines
- Kerbal Space Program
- Besiege
- Sheltered
- Stardew Valley
- Staxel
- Total Miner
- Ravenfield
- The Ultimate Nerd Game
- Unturned

It is also used in unit testing Windows Presentation Foundation controls and in many other areas.

If you develop in C# and your code is loaded as a module/plugin into a host application, you can use Harmony to alter the functionality of all the available assemblies of that application. Where other patch libraries simply allow you to replace the original method, Harmony goes one step further and gives you:

* A way to keep the original method intact

* Execute your code before and/or after the original method

* Modify the original with IL code processors

* Multiple Harmony patches co-exist and don't conflict with each other

**Installation**  
Installation is usually done by referencing the **0Harmony.dll** (from the zip file) from your project or by using the **[Lib.Harmony](https://www.nuget.org/packages/Lib.Harmony)** nuget package.

**Documentation**  
Please check out the **[documentation](https://harmony.pardeike.net)** or join us at the official **[discord server](https://discord.gg/xXgghXR)**.

**Contributions**  
This project uses the fantastic library of 0x0ade [MonoMod.Common](https://github.com/MonoMod/MonoMod.Common). Without it, we would still be stuck with using dynamic methods!

<hr>

**Help by promoting this library** so other developers can find it. One way is to upvote **[this stackoverflow answer](https://stackoverflow.com/questions/7299097/dynamically-replace-the-contents-of-a-c-sharp-method/42043003#42043003)**. Or spread the word in your developer communities. Thank you!

For more information from me and my other open source projects, follow me on twitter: @pardeike

Hope you enjoy Harmony!
