# MiBand8_WatchFace_Colorful_Lines

## Preview

![](images/P1_preview.png)
![](images/P2_preview.png)
![](images/P3_preview.png)
![](images/P4_preview.png)

## How to compile?

1. Download [EasyFace v4.15](https://github.com/m0tral/EasyFace/releases/tag/v4.15). Then decompress it.
2. Edit the `DeviceInfo.db` file in the EasyFace directory in text format.

> 1. Find the section for `Mi Band 8`;
> 2. Add new lines in the `SourceDataList` section:

```xml
<SRC ID="1112"    Name="Month Low"                FaceProgramma_Version="0" Device_Version="1.0.0" UsingNewFileTypeID_En="0" Tip=""/>
<SRC ID="1212"    Name="Month High"               FaceProgramma_Version="0" Device_Version="1.0.0" UsingNewFileTypeID_En="0" Tip=""/>
<SRC ID="0941"    Name="Battery percent ones"     FaceProgramma_Version="0" Device_Version="1.0.0" UsingNewFileTypeID_En="0" Tip=""/>
<SRC ID="1000941" Name="Battery percent tens"     FaceProgramma_Version="0" Device_Version="1.0.0" UsingNewFileTypeID_En="0" Tip=""/>
<SRC ID="2000941" Name="Battery percent hundreds" FaceProgramma_Version="0" Device_Version="1.0.0" UsingNewFileTypeID_En="0" Tip=""/>
```

3. Launch the `EasyFace.exe`.
4. Open `CLines.fprj`.
5. Click the "Compile" button to start compiling. The generated files are located in the `./output` directory.
