# Examples

This directory contains examples demonstrating how to use the Behavioral Signals Python SDK.

## 🚀 Quick Start: Colab Demo

The easiest way to get started is with our interactive Colab notebook:

### Option 1: Open directly in Google Colab

1. **Click this link**: [Open demo_colab.ipynb in Colab](https://colab.research.google.com/github/apetrogianni/behavioralsignals-python/blob/main/examples/demo_colab.ipynb)

2. **Enter your API credentials** in the second code cell:

   ```python
   CID = "your_cid_here"
   API_KEY = "your_api_key_here"
   ```

3. **Run all cells** by clicking `Runtime > Run all` or pressing `Ctrl+F9`

That's it! The notebook will:

- Install dependencies automatically
- Load sample audio from HuggingFace
- Demonstrate both batch and streaming APIs
- Show results with pretty formatting

### Option 2: Manual upload to Colab

1. Download the `demo_colab.ipynb` file
2. Go to [Google Colab](https://colab.research.google.com/)
3. Click `File > Upload notebook`
4. Upload the downloaded file
5. Follow steps 2-3 from Option 1 above

## 📁 Local Examples

If you prefer to run examples locally, see the subdirectories:

### Batch Mode Examples

- [batch/batch_api_polling.py](batch/batch_api_polling.py) - Process complete audio files
- [batch/batch_upload_dataset.py](batch/batch_upload_dataset.py) - Evaluate entire datasets
- See [batch/README.md](batch/README.md) for setup instructions

### Streaming Mode Examples

- [streaming/streaming_api_file.py](streaming/streaming_api_file.py) - Stream from audio file
- [streaming/streaming_from_mic.py](streaming/streaming_from_mic.py) - Stream from microphone
- See [streaming/README.md](streaming/README.md) for setup instructions

## 🔑 Getting API Credentials

To use any of these examples, you'll need:

- **CID** (Customer ID)
- **API_KEY**

Contact [Behavioral Signals](https://behavioralsignals.com) to obtain your credentials.

## 💡 Which Example Should I Use?

- **New to the SDK?** → Start with `demo_colab.ipynb`
- **Need to process files?** → Use batch mode examples
- **Real-time analysis?** → Use streaming mode examples
- **Testing integration?** → All examples work great!
