# METADATOS DE IMAGENES E IA

Cuando le pedimos a ChatGPT que modifique una imagen, ¿que hace realmente?
Cuando le pides a una IA que modifique una imagen, estas generarán una nueva imagen en base a la imagen que tu le has pasado.
Y al ser una imagen completamente nueva, los metadatos son diferentes a los de la imagen original.

Para poder comprobar esto, use la siguiente imagen:

<details>
<summary>Ver imagen</summary>
  
![real](https://github.com/user-attachments/assets/7de3b356-1cbc-4745-817d-3679e9d15c97)
</details>

Esta imagen contiene un termómetro, que marca una temperatura de 39,3 grados, apareciendo en la foto, unos dedos y un teclado con iluminación roja.

Para poder obtener los metadatos, he usado la herramienta **exif-tool** en un equipo Kali Linux, con el comando:

```bash
exiftool 1.jpg
```

<details>
<summary>Metadatos de la imagen 📸</summary>

- ExifTool Version Number         : 13.25
- File Name                       : 1.jpg
- Directory                       : .
- File Size                       : 2.3 MB
- File Modification Date/Time     : 2025:11:24 02:42:29-05:00
- File Access Date/Time           : 2025:11:24 02:55:27-05:00
- File Inode Change Date/Time     : 2025:11:24 02:42:29-05:00
- File Permissions                : -rwxrwxrwx
- File Type                       : JPEG
- File Type Extension             : jpg
- MIME Type                       : image/jpeg
- JFIF Version                    : 1.01
- Exif Byte Order                 : Little-endian (Intel, II)
- Make                            : realme
- Camera Model Name               : realme GT 2
- Orientation                     : Horizontal (normal)
- X Resolution                    : 72
- Y Resolution                    : 72
- Resolution Unit                 : inches
- Modify Date                     : 2025:11:17 16:27:52
- Y Cb Cr Positioning             : Centered
- Interoperability Index          : R98 - DCF basic file (sRGB)
- Interoperability Version        : 1.0
- Exposure Time                   : 1/25
- F Number                        : 1.8
- Exposure Program                : Not Defined
- ISO                             : 500
- Exif Version                    : 0220
- Date/Time Original              : 2025:11:17 16:27:52
- Create Date                     : 2025:11:17 16:27:52
- Offset Time Original            : +01:00
- Components Configuration        : Y, Cb, Cr, -
- Shutter Speed Value             : 1/25
- Aperture Value                  : 1.8
- Brightness Value                : undef
- Exposure Compensation           : 0
- Max Aperture Value              : 1.8
- Metering Mode                   : Center-weighted average
- Flash                           : Off, Did not fire
- Focal Length                    : 5.6 mm
- Maker Note Unknown Text         : (Binary data 232 bytes, use -b option to extract)
- User Comment                    : oplus_32
- Sub Sec Time                    : 585
- Sub Sec Time Original           : 585
- Sub Sec Time Digitized          : 585
- Flashpix Version                : 0100
- Color Space                     : sRGB
- Exif Image Width                : 0
- Exif Image Height               : 0
- Sensing Method                  : Not defined
- Scene Type                      : Unknown (0)
- Exposure Mode                   : Auto
- White Balance                   : Auto
- Digital Zoom Ratio              : 0
- Focal Length In 35mm Format     : 24 mm
- Scene Capture Type              : Standard
- Lens Model                      : realme GT 2 back camera 5.59mm f/1.8
- Profile CMM Type                : Apple Computer Inc.
- Profile Version                 : 4.0.0
- Profile Class                   : Display Device Profile
- Color Space Data                : RGB
- Profile Connection Space        : XYZ
- Profile Date Time               : 2018:06:24 13:22:32
- Profile File Signature          : acsp
- Primary Platform                : Apple Computer Inc.
- CMM Flags                       : Not Embedded, Independent
- Device Manufacturer             : Unknown (OPPO)
- Device Model                    :
- Device Attributes               : Reflective, Glossy, Positive, Color
- Rendering Intent                : Perceptual
- Connection Space Illuminant     : 0.9642 1 0.82491
- Profile Creator                 : Apple Computer Inc.
- Profile ID                      : 0
- Profile Description             : Display P3
- Profile Copyright               : Copyright Apple Inc., 2017
- Media White Point               : 0.95045 1 1.08905
- Red Matrix Column               : 0.51512 0.2412 -0.00105
- Green Matrix Column             : 0.29198 0.69225 0.04189
- Blue Matrix Column              : 0.1571 0.06657 0.78407
- Red Tone Reproduction Curve     : (Binary data 32 bytes, use -b option to extract)
- Chromatic Adaptation            : 1.04788 0.02292 -0.0502 0.02959 0.99048 -0.01706 -0.00923 0.01508 0.75168
- Blue Tone Reproduction Curve    : (Binary data 32 bytes, use -b option to extract)
- Green Tone Reproduction Curve   : (Binary data 32 bytes, use -b option to extract)
- Image Width                     : 3072
- Image Height                    : 4096
- Encoding Process                : Baseline DCT, Huffman coding
- Bits Per Sample                 : 8
- Color Components                : 3
- Y Cb Cr Sub Sampling            : YCbCr4:2:0 (2 2)
- JSON Info                       : [{"length":4,"name":"private.emptyspace","offset":51,"version":1},{"length":47,"name":"watermark.device","offset":47,"version":1}]
- Device                          : 0xcdcc8c3f00 realme GT 2
- Aperture                        : 1.8
- Image Size                      : 3072x4096
- Megapixels                      : 12.6
- Scale Factor To 35 mm Equivalent: 4.3
- Shutter Speed                   : 1/25
- Create Date                     : 2025:11:17 16:27:52.585
- Date/Time Original              : 2025:11:17 16:27:52.585+01:00
- Modify Date                     : 2025:11:17 16:27:52.585
- Circle Of Confusion             : 0.007 mm
- Field Of View                   : 73.7 deg
- Focal Length                    : 5.6 mm (35 mm equivalent: 24.0 mm)
- Hyperfocal Distance             : 2.48 m
- Light Value                     : 4.0
- Lens ID                         : realme GT 2 back camera 5.59mm f/1.8
</details>

Ahora le preguntaré a ChatGPT y a Gemini que modifiquen la imagen, para que el termómetro marque 41.4 grados en vez de 39.3 grados.

## GEMINI

**Prompt**: Quiero que cambies la temperatura del termómetro y que marque 41,4 grados.

<details>
<summary>Resultado</summary>

<img width="864" height="1184" alt="gemini" src="https://github.com/user-attachments/assets/7808c274-42ed-43b7-a361-e7ab58db9d35" />
</details>

Se puede observar, que no ha realizado bien la edición de la imagen, además de que ha añadido una marca de agua.

<details>
<summary>Ver metadatos de la imagen 🖼️ </summary>

- ExifTool Version Number         : 13.25
- File Name                       : 1_ia.jpg
- Directory                       : .
- File Size                       : 1135 kB
- File Modification Date/Time     : 2025:11:24 02:55:26-05:00
- File Access Date/Time           : 2025:11:24 02:55:53-05:00
- File Inode Change Date/Time     : 2025:11:24 02:55:26-05:00
- File Permissions                : -rwxrwxrwx
- File Type                       : PNG
- File Type Extension             : png
- MIME Type                       : image/png
- Image Width                     : 864
- Image Height                    : 1184
- Bit Depth                       : 8
- Color Type                      : RGB
- Compression                     : Deflate/Inflate
- Filter                          : Adaptive
- Interlace                       : Noninterlaced
- Significant Bits                : 8 8 8
- Exif Byte Order                 : Little-endian (Intel, II)
- Orientation                     : Horizontal (normal)
- Software                        : Picasa
- Exif Version                    : 0220
- Color Space                     : sRGB
- Exif Image Width                : 864
- Exif Image Height               : 1184
- Interoperability Index          : R98 - DCF basic file (sRGB)
- Interoperability Version        : 0100
- Image Unique ID                 : 9b4d6d7a65e4fc960000000000000000
- X Resolution                    : 72
- Y Resolution                    : 72
- Resolution Unit                 : inches
- Thumbnail Offset                : 294
- Thumbnail Length                : 5029
- XMP Toolkit                     : XMP Core 5.5.0
- Date/Time Original              : 2025:11:24 07:53:42+00:00
- Digital Source File Type        : http://cv.iptc.org/newscodes/digitalsourcetype/compositeWithTrainedAlgorithmicMedia
- Digital Source Type             : http://cv.iptc.org/newscodes/digitalsourcetype/compositeWithTrainedAlgorithmicMedia
- Credit                          : Edited with Google AI
- Date Created                    : 2025:11:24 07:53:42+00:00
- Warning                         : JUMBFBox pointer references previous IFD0 directory
- Image Size                      : 864x1184
- Megapixels                      : 1.0
- Thumbnail Image                 : (Binary data 5029 bytes, use -b option to extract)

</details>

### DIFERENCIAS

#### ORIGEN Y AUTENTICIDAD

**Imagen real**

- Make: realme
- Camera Model Name: realme GT 2

**Gemini**

- Software: Picasa
- Credit: Edited with Google AI
- Digital Source Type: compositeWithTrainedAlgorithmicMedia

#### FORMATO Y TAMAÑO

**Imagen real**

- File Type: JPEG
- File Size: 2.3 MB
- Image Size: 3072x4096 - 12.6 mpx

**Gemini**

- File Type: PNG
- File Size: 1135 kB
- Image Size: 864x1184 - 1 mpx

#### DATOS TÉCNICOS DE LA CÁMARA

**Imagen real**

- Exposure Time: 1/25
- F Number: 1.8
- ISO: 500
- Focal Length: 5.6 mm
- Lens Model: realme GT 2 back camera 5.59mm f/1.8

**Gemini**

- No existen

#### FECHAS

**Imagen real**

- Date/Time Original: 2025:11:17 16:27:52
- Create Date: 2025:11:17 16:27:52

**Gemini**

- Date/Time Original: 2025:11:24 07:53:42+00:00

## CHATGPT

**Prompt**: Quiero que cambies la temperatura del termómetro y que marque 41,4 grados.

<details>
<summary>Resultado</summary>

<img width="1024" height="1536" alt="chatgpt" src="https://github.com/user-attachments/assets/bda6cfc9-740a-449f-a7ca-3146ce734f82" />
</details>

Se puede observar que ha generado toda la imagen de nuevo, incluyendo el termómetro, el teclado, mis dedos, etc

<details>
<summary>Ver metadatos de la imagen 🖼️ </summary>

- ExifTool Version Number         : 13.25
- File Name                       : chatgpt.png
- Directory                       : .
- File Size                       : 2.5 MB
- File Modification Date/Time     : 2025:11:24 03:28:08-05:00
- File Access Date/Time           : 2025:11:24 07:52:13-05:00
- File Inode Change Date/Time     : 2025:11:24 03:28:08-05:00
- File Permissions                : -rwxrwxrwx
- File Type                       : PNG
- File Type Extension             : png
- MIME Type                       : image/png
- Image Width                     : 1024
- Image Height                    : 1536
- Bit Depth                       : 8
- Color Type                      : RGB
- Compression                     : Deflate/Inflate
- Filter                          : Adaptive
- Interlace                       : Noninterlaced
- JUMD Type                       : (c2pa)-0011-0010-800000aa00389b71
- JUMD Label                      : c2pa
- Actions Action                  : c2pa.created, c2pa.converted
- Actions Software Agent Name     : GPT-4o
- Actions Digital Source Type     : http://cv.iptc.org/newscodes/digitalsourcetype/trainedAlgorithmicMedia
- Exclusions Start                : 33
- Exclusions Length               : 14124
- Name                            : jumbf manifest
- Alg                             : sha256
- Hash                            : (Binary data 32 bytes, use -b option to extract)
- Pad                             : (Binary data 8 bytes, use -b option to extract)
- Instance ID                     : xmp:iid:09defea6-5e6f-46c4-bc57-4d1a8391d854
- Claim Generator Info Name       : ChatGPT
- Claim Generator Info Org Contentauth C2 Pa Rs: 0.0.0
- Signature                       : self#jumbf=/c2pa/urn:c2pa:3ef72d8d-1839-4cbc-8cb4-fa7baf8c0d7b/c2pa.signature
- Created Assertions Url          : self#jumbf=c2pa.assertions/c2pa.actions.v2, self#jumbf=c2pa.assertions/c2pa.hash.data
- Created Assertions Hash         : (Binary data 32 bytes, use -b option to extract), (Binary data 32 bytes, use -b option to extract)
- Title                           : image.png
- Item 0                          : (Binary data 1985 bytes, use -b option to extract)
- Item 1 Pad                      : (Binary data 10932 bytes, use -b option to extract)
- Item 2                          : null
- Item 3                          : (Binary data 64 bytes, use -b option to extract)
- C2PA Thumbnail Ingredient Salt  : e4efdb2c20bc1ff69d3f2207ac100449
- C2PA Thumbnail Ingredient Type  : image/jpeg
- C2PA Thumbnail Ingredient Data  : (Binary data 21682 bytes, use -b option to extract)
- Relationship                    : parentOf
- Format                          : png
- Validation Results Active Manifest Success Code: claimSignature.insideValidity, claimSignature.validated, assertion.hashedURI.match, assertion.hashedURI.match, assertion.dataHash.match
- Validation Results Active Manifest Success Url: self#jumbf=/c2pa/urn:c2pa:3ef72d8d-1839-4cbc-8cb4-fa7baf8c0d7b/c2pa.signature, self#jumbf=/c2pa/urn:c2pa:3ef72d8d-1839-4cbc-8cb4-fa7baf8c0d7b/c2pa.signature, self#jumbf=/c2pa/urn:c2pa:3ef72d8d-1839-4cbc-8cb4-fa7baf8c0d7b/c2pa.assertions/c2pa.actions.v2, self#jumbf=/c2pa/urn:c2pa:3ef72d8d-1839-4cbc-8cb4-fa7baf8c0d7b/c2pa.assertions/c2pa.hash.data, self#jumbf=/c2pa/urn:c2pa:3ef72d8d-1839-4cbc-8cb4-fa7baf8c0d7b/c2pa.assertions/c2pa.hash.data
- Validation Results Active Manifest Success Explanation: claim signature valid, claim signature valid, hashed uri matched: self#jumbf=c2pa.assertions/c2pa.actions.v2, hashed uri matched: self#jumbf=c2pa.assertions/c2pa.hash.data, data hash validActive Manifest Url             : self#jumbf=/c2pa/urn:c2pa:3ef72d8d-1839-4cbc-8cb4-fa7baf8c0d7b
- Active Manifest Alg             : sha256
- Active Manifest Hash            : (Binary data 32 bytes, use -b option to extract)
- Claim Signature Url             : self#jumbf=/c2pa/urn:c2pa:3ef72d8d-1839-4cbc-8cb4-fa7baf8c0d7b/c2pa.signature
- Claim Signature Alg             : sha256
- Claim Signature Hash            : (Binary data 32 bytes, use -b option to extract)
- Thumbnail URL                   : self#jumbf=c2pa.assertions/c2pa.thumbnail.ingredient
- Thumbnail Hash                  : (Binary data 32 bytes, use -b option to extract)
- Actions Parameters Ingredients Url: self#jumbf=c2pa.assertions/c2pa.ingredient.v3
- Actions Parameters Ingredients Hash: (Binary data 32 bytes, use -b option to extract)
- Image Size                      : 1024x1536
- Megapixels                      : 1.6

</details>

### DIFERENCIAS

#### ORIGEN Y AUTENTICIDAD

**Imagen real**

- Make: realme
- Camera Model Name: realme GT 2

**CHATGPT**

- Actions Software Agent Name: GPT-4o
- Claim Generator Info Name: ChatGPT
- Digital Source Type: trainedAlgorithmicMedia

#### FORMATO Y TAMAÑO

**Imagen real**

- File Type: JPEG
- File Size: 2.3 MB
- Image Size: 3072x4096 - 12.6 mpx

**CHATGPT**

- File Type: PNG
- File Size: 2.5 MB
- Image Size: 1024x1536 - 1.6 mpx

#### DATOS TÉCNICOS DE LA CÁMARA

**Imagen real**

- Exposure Time: 1/25
- F Number: 1.8
- ISO: 500
- Focal Length: 5.6 mm
- Lens Model: realme GT 2 back camera 5.59mm f/1.8

**CHATGPT**

- No existen

#### FECHAS

**Imagen real**

- Date/Time Original: 2025:11:17 16:27:52
- Create Date: 2025:11:17 16:27:52

**CHATGPT**

- File Modification Date/Time: 2025:11:24 03:28:08-05:00
