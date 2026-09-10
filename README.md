# MiSTer Organize

Tutorial Video: https://www.youtube.com/watch?v=mjGUGqpZ2uU

MiSTer Organize is a vibrant community dedicated to ROM management and organization. We're building custom DATs for RomVault, tailored to the MiSTer FPGA but adaptable for other emulation setups. Everyone's invited to contribute—your input makes a real difference! I share public updates on the 7th of every month, featuring fresh DATs you can grab from the Discord News Channel. Supporters unlock exclusive perks, like a private DAT and access to hidden server channels.

Before diving in, swing by the Discord Welcome Channel to review our Rules and Server Roles. Then head to Channels & Roles to opt into contributing or volunteering as a tech support.

Got questions? Drop into the Discord Support Tickets Channel and hit the ‘Open ticket’ button to chat with staff. For more details, explore the project on GitHub: https://github.com/MiSTerOrganize/MiSTer_Organize.

Support me on Patreon:

https://www.patreon.com/MiSTer_Organize

Find me on Twitter and Discord:

https://x.com/MiSTerOrganize

https://discord.gg/rUXVkAsYue

# Getting Started

WARNING: Never move your ROM files into the RomVault ToSort folder, always use a copy. I am not responsible for the loss of files if this strongly suggested rule has not been respected.

Head to the project's Patreon and grab the latest update ZIP file. Right-click the downloaded file and select "Extract All" to unzip it. Relocate the extracted folder to your preferred ROM storage spot—I highly recommend a spacious option like a 5TB hard drive or NAS, given the project's massive file collection.

Open the folder on your storage device. You'll find a sources subfolder — _Public Sources in the public update, _Exclusive Sources in the exclusive one — packed with plain-text docs listing ROM download links, one per DAT category. For more sources, check the MiSTer Organize Log Channel on Discord.

Next, dive into the MiSTer Organize folder. It includes the pre-configured RomVault app, ready for the project, plus three key folders: DatRoot (holds the DAT files that guide ROM organization), RomRoot (stores essential MiSTer files like RBFs and MGLs, plus your sorted ROMs), and ToSort (where you'll drop unsorted ROMs for processing).

Once your ROMs are in ToSort, launch RomVault. On the left sidebar, hit these buttons in order:

1. Update DATs—loads the latest DAT files.
2. Scan ROMs—analyzes your files.
3. Find Fixes—identifies organization tweaks.
4. Fix ROMs—shifts everything from ToSort to RomRoot in tidy folders.

Finally, copy the sorted folders to your MiSTer storage device. Every set matches MiSTer's exact folder structure for seamless integration, so you can copy across whichever ones you collect: MiSTer_Console, MiSTer_Console_CD (or MiSTer_Console_CD_CHD if you prefer CHD), MiSTer_Computer, MiSTer_Arcade with MiSTer_Arcade_MAME and MiSTer_Arcade_HBMAME, and MiSTer_Extras, which carries the MiSTer system files themselves — cores, MGLs, filters, presets, palettes, borders and docs.

Supporters also get the private sets: MiSTer_Console_Private, MiSTer_Extras_Private and MiSTer_Frontier.

# What is a DAT?

Short for "data files", they're called DATs or DAT files because they usually have the extension .dat. They contain a catalog of titles and attributes for each of its titles, including file names, hashes, and sizes.

Used in combination with a ROM manager, the information in a DAT file can be used to audit files on your hard drive to ensure that they are named correctly, and that they match the recorded attributes in the file.

DAT files usually follow one of two standards: either a variant on the XML-based LogiqX format, or the less commonly used CLRMAMEPro format. There are many more less common formats.

# What is RomVault?

RomVault is a tool for ROM management. It works with DAT files to sort the ROMs into folders. The DAT I provide is telling the files where they need to go. Let’s take the example of the Shinobi Neo Geo game. When you click Fix ROMs, Shinobi Neo Geo will go into the Neo Geo Core folder and then into the Unlicensed games folder. This all happens because that is the file destination I have set in the DAT file.

# RomVault Releases

https://www.romvault.com/

# RomVault Windows Setup

https://wiki.romvault.com/doku.php?id=install_and_setup

# RomVault Linux Setup

https://wiki.romvault.com/doku.php?id=linux_setup

# RomVault Side Buttons

https://wiki.romvault.com/doku.php?id=side_buttons

# Console CHD

The project supports CHD format for your Console CD games and a MiSTer_Console_CD_CHD DAT. This is made possible through the MiSTer CHD Converter tool, included in your update folder and originally designed by TeamC. Point it at your BIN/CUE folder and it converts each disc to a single CHD file. There is a 50-60% size reduction with CHD compared to BIN/CUE, which helps save on storage space. You may want to archive your BIN/CUE sets and copy the CHD sets to your MiSTer.

The converter uses the exact chdman settings the shared DAT was built with, so the CHDs it produces match the MiSTer_Console_CD_CHD DAT and verify green in RomVault. It converts one way, BIN/CUE to CHD; if you ever need to go back, chdman itself will do it with chdman extractcd -i disc.chd -o disc.cue -sb. Stop anytime — it finishes the current disc, then stops — and re-run to continue where it left off. Big thanks goes out to TeamC for his efforts with CHD.

# MiSTer Delta Sync

Also included in your update folder. When a new release comes out, you don't need to re-copy your whole library to your MiSTer drive or NAS — MiSTer Delta Sync compares the old and new DATs and copies across only what actually changed. It updates your DATs for you, keeps the previous ones in a DAT Archive so you can roll back, and can also rebuild a drive that has drifted out of sync. Supporters can sign in with Patreon from inside the tool to unlock the private DATs.

# RetroNAS

MiSTer Organize is available as a service in RetroNAS. So users who have RetroNAS serving their games over the network can enable the service to help organize their games.

RetroNAS Wiki Links:

https://github.com/retronas/retronas/wiki/MiSTer-FPGA

https://github.com/retronas/retronas/wiki/MiSTer-Organize

# Show Your Support

Loving this project? Support me here, https://www.patreon.com/MiSTer_Organize

# Credits

MiSTer Organize creator of MiSTer Organize.

Alexey Melnikov creator of MiSTer FPGA project.

All other MiSTer FPGA developers for giving us the ultimate retro gaming experience.

José Manuel Barroso Galindo for Update All script.

MiSTer Addons for giving us quality accessories for the MiSTer FPGA project.

Taki Udon for giving us affordable options for the MiSTer FPGA project.

Lu's Retro Source for providing news about the MiSTer FPGA project.

Pixel Cherry Ninja for providing news about the MiSTer FPGA project.

Bob founder of RetroRGB for providing news about the retro-gaming community.

No-Intro for its database of best available ROMs and digital games.

Redump for its disc preservation database.

Hardware Target Game Database for archival efforts of the highest quality ROM dumps.

ScreenScraper.fr for its game database.

GordonJ creator of RomVault.

Roman Scherzer creator of CLRMAMEPro.

Unexpectedpanda creator of Retool.

Matt Nadareski creator of SabreTools.

Asphodel creator of Universal ROM Sorter.

GamaBurst for assistance and contributions to the project.

TeamC for assistance and contributions to the project.

^c|0ud^ for assistance and contributions to the project.

RetroNAS Team for adding MiSTer Organize support.

Big thank you to all my Patreon supporters! Your support is sincerely appreciated!
