# Pdf-to-Doc-txt-conversion-Google-Colab

# Use google colab to Convert pdf file to doc or txt
Tired of adds while converting pdf to doc, using third party websites or apps?
Try this script to convert your pdf to doc or txt using google colab notebook.
The script uses libreoffice and tesseract module of python to convert pdf to doc or txt, 

<a href="https://colab.research.google.com/drive/1AAB1otg-G0TM98V6-y_oA3a27cPFEifr?usp=sharing"
   target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

### Tutorial
1. Click the badge which says 'Open in Colab'.
2. Run the first cell titled "Run This cell"
3. In second cell choose the Convert_File_type before running the cell
4. Run the second cell
5. Upload the pdf file that you want to convert, from the local machine.
6. Wait till the file is converted and downloaded

### What is the purpose of it?
1. High bandwidth from google servers
2. Avoid advertisements while converting pdf files from third party websites.
3. Keeping confidentiality of files during conversion since we are using google colab.
4. This script was made mainly for learing purpose.

### Frequently Asked Questions

1. **How to get editable text from scanned pdf or pdf with images?**: 

Select 'txt' from Convert_to_type before running the second cell. scince script uses pytesseract for recongnising the text from image files
there may be some losses of text while converion.

2. **How to convert pdf to files other than doc or text?**: 

you can change the --convert-to file_type(doc) argument given to libreoffice command in the code to available file types in libreoffice.


# This whole repo is against Google Colab policy and you shouldn't be using it.
> **Why are hardware resources such as T4 GPUs not available to me?**
The best available hardware is prioritized for users who use Colaboratory interactively rather than for long-running computations. Users who use Colaboratory for long-running computations may be temporarily restricted in the type of hardware made available to them, and/or the duration that the hardware can be used for. We encourage users with high computational needs to use Colaboratory’s UI with a local runtime.
Please note that using Colaboratory for cryptocurrency mining is disallowed entirely, and may result in being banned from using Colab altogether.

<sub>Source: https://research.google.com/colaboratory/faq.html</sub>

### Maintained By : [Lokesh J](https://www.linkedin.com/in/lokesh-j-13b844140/)
