# large-v2-002.pt
This repository contains the large-v2 model for the Whisper neural network.

### English Description
This repository contains the large-v2 model for the Whisper neural network. The model file, large-v2-002.pt, is too large (3 GB) to be uploaded as a single file on GitHub. To overcome this limitation, the model file has been split into smaller parts, each of which is no larger than 90 MB. The split model files are named large-v2-002_partaa, large-v2-002_partab, and so on.

If you wish to use the complete large-v2 model, you will need to reassemble the split parts using the provided build instructions below.

### Русское описание
Этот репозиторий содержит модель large-v2 для нейросети Whisper. Файл модели large-v2-002.pt имеет слишком большой размер (3 ГБ) для загрузки в GitHub в виде одного файла. Чтобы обойти это ограничение, файл модели был разделен на более мелкие части, каждая из которых не превышает 90 МБ. Разделенные файлы модели названы large-v2-002_partaa, large-v2-002_partab и так далее.

Если вы хотите использовать полную модель large-v2, вам нужно будет объединить разделенные части с помощью предоставленных инструкций ниже.

### Build Instructions
To reconstruct the complete large-v2 model from the split parts, follow these instructions:

1. Clone this repository to your local machine using `git clone https://github.com/alex625051/large-v2-002.pt.git`.

2. Navigate to the repository folder: `cd large-v2-002.pt`.

3. Use the following command to concatenate the split parts and reconstruct the complete model:
   ```
   cat large-v2-002_part* > large-v2-002.pt
   ```

   This command will combine all the split parts into a single file named large-v2-002.pt.

4. The large-v2-002.pt file now contains the complete Whisper large-v2 model, and you can use it for your neural network applications.

Please note that you can change "your_username" and "your_repository" in the clone command to match your GitHub username and repository name, respectively.

**Note**: Ensure that you have enough free disk space to accommodate both the split parts and the final reconstructed large-v2 model file.
