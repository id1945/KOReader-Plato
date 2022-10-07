# KOReader-Plato
## Install Packages for KOReader & Plato

| Name | Link |
| ------ | ------ |
| Koreader | https://github.com/koreader/koreader |
| Plato | https://github.com/baskerville/plato |
| Kfmon | https://github.com/NiLuJe/kfmon |

<div id="post_message_3797095" class="vb_postbit">
			
You'll find here links to so called <b>"one-click"</b> install packages for both <a href="https://github.com/koreader/koreader">KOReader</a> &amp; <a href="https://github.com/baskerville/plato">Plato</a>.<br>
This is primarily aimed at brand new users, with the goal of getting things to work in the most fool-proof manner possible, by simply unpacking a single ZIP archive in the root of your Kobo eReader over USB.<br>
To make this possible, these packages bundle <a href="https://github.com/NiLuJe/kfmon">KFMon</a> &amp; <a href="https://www.mobileread.com/forums/showthread.php?t=329525">NickelMenu</a>.<br>
<br>
For existing users, if you're happy with your current setup, by all means, carry on! <img src="https://www2.mobileread.com/i/smilies/wink.gif" border="0" alt="" title="Wink" class="inlineimg">. Launchers are, by design, mutually exclusive: between fmon &amp; KFMon, only the one installed <i>last</i> will be active, but where KSM is concerned, KSM will <i>always</i> take precedence, so this is <b>NOT</b> designed for KSM users.<br>
If you're curious as to what this actually <i>does</i> to original KOreader/Plato packages, the gory details are <a href="https://github.com/NiLuJe/kfmon/blob/master/tools/one-click.py">all here</a>!<br>
<br>
Now that this is out of the way, on to the good stuff!<br>
<br>
As mentioned earlier, the installation instructions are dead simple, and can be <span style="color:Green">automated by the script found in <a href="https://www.mobileread.com/forums/showpost.php?p=3797096&amp;postcount=2">post #2</a></span>:<ol style="list-style-type: decimal"><li> Choose what you want to install: KOReader, Plato, or both, and download the appropriate ZIP from the listing below.</li>
<li> Plug your Kobo eReader to your computer over USB.</li>
<li> Directly extract the ZIP archive you've just downloaded to the <i>root</i> directory of your device (i.e., not under <i>any</i> subdirectory). <span style="color:DarkGrey">(That's the <b>"one click"</b> bit ;p)</span><br>
   NOTE: Prefer the "Extract To" approach (and allow replacing existing content if it's asked of you) vs. manually copy/pasting or drag'n dropping bits of the ZIP content yourself, as preserving the integrity of the directory structure and its contents is of paramount importance!</li>
<li> <span style="color:Red"><b>NOTE:</b></span> On FW &gt;= 4.17, you'll need to <a href="https://github.com/NiLuJe/kfmon/blob/afd320d572e250315c0a0d1110cf8b1b321c4a27/tools/install.sh#L114-L130">prevent Nickel from scanning *nix hidden folders</a>.</li>
<li> Safely eject your device. The Kobo software should then appear to be processing a book, before restarting to process an update.<br>
   NOTE: If it <i>doesn't</i> attempt to reboot, that's a sure thing something went wrong in the previous step (hint: see the NOTE).</li>
<li> Once your device has finished rebooting, you should simply be able to tap on the KOReader or Plato icon in your Home or your Library to launch it, or via the new entries added to the Home's main menu!</li>
</ol><br>
<b>NOTE:</b> Something that bears repeating from <a href="https://github.com/NiLuJe/kfmon#things-to-watch-out-for">KFMon's FAQ</a>: a FW update will <i>disable</i> it, so you'll have to reinstall it after a FW update in order to be able to launch stuff again, which is why there's a package dedicated to that listed at the bottom of this post.<br>
<br>
<span style="color:Red"><b>NOTE:</b></span> Another thing that bears repeating is that on FW &gt;= 4.17, you'll probably also want to <a href="https://github.com/NiLuJe/kfmon/blob/afd320d572e250315c0a0d1110cf8b1b321c4a27/tools/install.sh#L114-L130">prevent Nickel from scanning *nix hidden folders</a>. And you'll want to tweak your config <i>before</i> unplugging your device (i.e., before installing this; or, if you've just upgraded your FW, during the first USB connection after the update).<br>
<br>
<span style="color:Green"><b>NOTE:</b></span> Please see the <a href="https://www.mobileread.com/forums/showpost.php?p=3797096&amp;postcount=2">next post</a> for an automated installation script, which I heartily recommend using instead of doing all this manually!<br>
<br>
<br>
The listing follows this format:<br>
<b>Description</b>  |  <b>D/L Link</b>  |  <b>Last Modified</b>  |  <b>Size</b>  |  <b>MD5 Checksum</b>  |  <b>MR Thread</b><br>
<br>
<span style="color:DarkGrey"><i>(A barebones version of this listing is also available <a href="https://storage.gra.cloud.ovh.net/v1/AUTH_2ac4bfee353948ec8ea7fd1710574097/kfmon-pub/kfmon.html">here</a>).</i></span><br>
<br>
<span class="resize_4"><b><span style="text-decoration: underline">One-Click Kobo Packages:</span></b></span><br>
<ul><li><span style="color:RoyalBlue"><b>KOReader</b></span>  <b>|</b>  <a href="https://storage.gra.cloud.ovh.net/v1/AUTH_2ac4bfee353948ec8ea7fd1710574097/kfmon-pub/OCP-KOReader-v2022.08.zip">OCP-KOReader-v2022.08.zip</a>  <b>|</b>  <i>2022-Aug-31 06:18:28</i>  <b>|</b>  42.4M  <b>|</b>  <span style="color:DimGray">d053a29397b73a6955aebe07577f5fd6</span>  <b>|</b>  <a href="https://www.mobileread.com/forums/forumdisplay.php?f=276">KOReader</a></li>
<li><span style="color:RoyalBlue"><b>Plato</b></span>  <b>|</b>  <a href="https://storage.gra.cloud.ovh.net/v1/AUTH_2ac4bfee353948ec8ea7fd1710574097/kfmon-pub/OCP-Plato-0.9.31.zip">OCP-Plato-0.9.31.zip</a>  <b>|</b>  <i>2022-Sep-03 13:02:55</i>  <b>|</b>  19.8M  <b>|</b>  <span style="color:DimGray">1e51d113d4faf4ac6a74442af1a73aad</span>  <b>|</b>  <a href="https://www.mobileread.com/forums/showthread.php?t=292914">Plato</a></li>
<li><span style="color:RoyalBlue"><b>KOReader AND Plato</b></span>  <b>|</b>  <a href="https://storage.gra.cloud.ovh.net/v1/AUTH_2ac4bfee353948ec8ea7fd1710574097/kfmon-pub/OCP-Plato-0.9.31_KOReader-v2022.08.zip">OCP-Plato-0.9.31_KOReader-v2022.08.zip</a>  <b>|</b>  <i>2022-Sep-21 22:32:54</i>  <b>|</b>  61.5M  <b>|</b>  <span style="color:DimGray">00bd1a289bf77a0c83db73d1d4ff74d9</span>  <b>|</b>  <a href="https://www.mobileread.com/forums/showthread.php?t=274231">KFMon</a></li>
<li><span style="color:RoyalBlue"><b>KFMon</b></span> (use this after a FW update)  <b>|</b>  <a href="https://storage.gra.cloud.ovh.net/v1/AUTH_2ac4bfee353948ec8ea7fd1710574097/kfmon-pub/OCP-KFMon-1.4.5-61-g9886423.zip">OCP-KFMon-1.4.5-61-g9886423.zip</a>  <b>|</b>  <i>2022-Sep-21 22:32:54</i>  <b>|</b>  782.0K  <b>|</b>  <span style="color:DimGray">50a7464369e648b6ebb20ab358e76094</span>  <b>|</b>  <a href="https://www.mobileread.com/forums/showthread.php?t=274231">KFMon</a></li>
</ul>
