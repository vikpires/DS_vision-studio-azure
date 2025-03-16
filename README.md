# Azure Vision Studio

> Challenge created as part of the Microsoft AI Fundamentals Bootcamp by DIO, based on the tutorials:

- [Detect faces in Vision Studio](https://aka.ms/ai900-face)
- [Read text in Vision Studio](https://aka.ms/ai900-ocr)
- [Analyze images in Vision Studio](https://aka.ms/ai900-image-analysis)

---

## 1. Detect Faces in Vision Studio

### 1.1. Provision an Azure AI services resource

- Start by provisioning an Azure AI services in the Azure portal.

- Search for `Azure AI services` in the Azure portal and create a new Azure AI services resource.

### 1.2. Connect Azure AI service resource to Vision Studio

- Navigate to [Vision Studio](https://portal.vision.cognitive.azure.com).

- On the Getting started with Vision landing page, select the **Face** tab and then select the **Detect Faces** in an image tile.

- Under the Try It Out subheading, acknowledge the resource usage policy by reading and checking the box.

<div align="center">
    <img src="./assets/vision-studio-interface-detect-faces.png" title="Vision Studio interface: Detect faces" width="75%" /> 
</div>

<div align="center">Vision Studio Interface - Detect Faces</div>

### 1.3. Upload the images

The following images can be found in the folder <a href= './inputs/detect-faces'>detect-faces</a>.

<div align="center">
    <img src="./inputs/detect-faces/store-camera-1.jpg" title="Woman and a girl in a grocery store" width="75%" />
</div>
<div align="center">Image 01</div>
<br />
<br />

<div align="center">
    <img src="./inputs/detect-faces/store-camera-2.jpg" title="Man, woman and girl in a grocery store" width="75%" /> 
</div>
<div align="center">Image 02</div>
<br />
<br />

<div align="center">
    <img src="./inputs/detect-faces/store-camera-3.jpg" title="A woman with her face covered for a sticker of a plant and a girl in a grocery store." width="75%" /> 
</div>
<div align="center">Image 03</div>

### 1.4. Output

**Detected Faces - Image 01:**

<div align="center">
    <img src="./output/detect-faces/store-camera-1.png" title="Detect face of the image 01" width="75%" />
</div>

<div align="center">
JSON attributes generated <a href= './output/detect-faces/image01-attributes.json'>here</a>.
</div>
<br />
<br />

**Detected Faces - Image 02:**

<div align="center">
    <img src="./output/detect-faces/store-camera-2.png" title="Detect face of the image 02" width="75%" />
</div>

<div align="center">
JSON attributes generated <a href= './output/detect-faces/image02-attributes.json'>here</a>.
</div>
<br />

**Detected Faces - Image 03:**

<div align="center">
    <img src="./output/detect-faces/store-camera-3.png" title="Detect face of the image 03" width="75%" />
</div>
<br />

```
No face detected
```

<br />

## 2. Read text in Vision Studio

### 2.1. Navigate to Vision Studio

- Navigate to [Vision Studio](https://portal.vision.cognitive.azure.com).

- On the Getting started with Vision landing page, **Optical character recognition**, and then the **Extract text from images tile**.

- Under the Try It Out subheading, acknowledge the resource usage policy by reading and checking the box.
<div align="center">
    <img src="./assets/vision-studio-interface-ocr.png" title="Vision Studio Interface: OCR" width="75%" />
</div>
<div align="center">Vision Studio Interface - OCR</div>

### 2.2. Upload the images

- The following images can be found in the folder <a href= './inputs/read-text-ocr'>read-text-ocr</a>.

<div align="center">
    <img src="./inputs/read-text-ocr/advert.jpg" title="Supermarket advert" width="75%" />
</div>
<div align="center">Image 01</div>
<br />

<div align="center"> 
    <img src="./inputs/read-text-ocr/receipt.jpg" title="Receipt"  width="50%" /> 
</div>
<div align="center">Image 02</div>

### 2.3. Outputs

**Extracted Text - Image 01:**

<div align="center">
    <img src="./output/read-text-ocr/advert-ocr.png" title="Supermarket advert's OCR" width="75%" />
</div>
<br />

```
NorthwindTraders
PIEWINNER
Freshproduce,
friendlyservice
Open7daysaweek

```

<div align="center"> 
JSON attributes generated <a href= './output/read-text-ocr/image01-attributes.json'>here</a>.
</div>
<br />
<br />

**Extracted Text - Image 02:**

<div align="center">
    <img src="./output/read-text-ocr/receipt-ocr.png" title="Receipt's OCR" width="75%" />
</div>
<br />

```
NorthwindTraders
123MainStreet
555-123-4567
2/17/202013:07
1Apple
$0.90
1Orange
$0.80
Sub-Total
$1.70
Tax
$0.17
Total
$1.87

```

<div align="center"> 
JSON attributes generated <a href= './output/read-text-ocr/image02-attributes.json'>here</a>.
</div>
<br />

## 3. Analyze images in Visual Studio

### 3.1. Navigate to Vision Studio

- Navigate to [Vision Studio](https://portal.vision.cognitive.azure.com).

- On the Getting started with _Vision_ landing page, **Image analysis**, and then the **Add captions to images**.

- Under the Try It Out subheading, acknowledge the resource usage policy by reading and checking the box.

<div align="center">
    <img src="./assets/vision-studio-interface-image-analysis.png" title="Vision Studio interface: Image analysis" width="75%" /> 
</div>
<div align="center">Vision Studio Interface - Image Analysis</div>

### 3.2. Upload the images

- The following images can be found in the folder <a href= './inputs/analyze-images'>analyze-images</a>.

<div align="center">
    <img src="./inputs/analyze-images/store-camera-1.jpg" title="Woman and a girl in a grocery store" width="75%" />
</div>
<div align="center">Image 01</div>
<br />

<div align="center"> 
    <img src="./inputs/analyze-images/store-camera-2.jpg" title="Woman in a supermarket" width="75%" /> 
</div>
<div align="center">Image 02</div>

### 3.3. Output

**Results - Image 01:**

<div align="center"> 
    <img src="./output/analyze-images/store-camera-1.png" title="Supermarket advert's OCR" width="75%" />
</div>
<br />

Caption:

```
A woman and a girl in a grocery store
```

JSON attributes generated <a href= "./output/analyze-images/store-camera-1-attributes.json">here</a>.
<br />
<br />

**Results - Image 02:**

<div align="center"> 
    <img src="./output/analyze-images/store-camera-2.png" title="Receipt's OCR" width="75%" />
</div>
<br />

Caption:

```
A woman holding a phone while shopping in a grocery store
```

<br />

JSON attributes generated <a href= "./output/analyze-images/store-camera-2-attributes.json">here</a>.
