# Hex to JSON and JSON to Hex Converter Using MessagePack

This tool allows you to convert Hexadecimal (Hex) strings to JSON objects and vice versa, utilizing MessagePack for encoding and decoding. It's designed to be a simple, user-friendly interface for working with data formats in development, debugging, or data analysis tasks.

The tool is hosted and can be accessed at [https://tecnicor.github.io/hex-json-converter-msgpack/](https://tecnicor.github.io/hex-json-converter-msgpack/).

## Features

- **Convert Hex to JSON:** Easily convert Hex strings to formatted JSON objects.
- **Convert JSON to Hex:** Convert JSON objects back into Hex strings.
- **Copy to Clipboard:** Quick copy functionality for both converted JSON and Hex outputs.
- **User-Friendly Interface:** Built with Tailwind CSS for a clean and responsive design.

## How It Works

The converter leverages the `msgpack-lite` JavaScript library to encode and decode data. MessagePack is an efficient binary serialization format that allows you to serialize and deserialize complex data structures more compactly than JSON.

### Converting Hex to JSON

1. Enter or paste the Hex string into the "Enter Hex Value" input field.
2. Click the "Convert to JSON" button. The corresponding JSON object will be displayed in the output area.
3. Use the "Copy" button to copy the JSON output to your clipboard.

### Converting JSON to Hex

1. Enter or paste the JSON object into the large textarea labeled "Enter JSON".
2. Click the "Convert to Hex" button. The Hex representation of the JSON object will be shown in the output area.
3. Use the "Copy" button beside the Hex output to copy the Hex string to your clipboard.

## How to Use This Tool with RedisInsight

1. Go to RedisInsight and navigate to the value you wish to update.
2. From the "Data Format" dropdown, choose "Hex".
3. Copy and paste the Hex value into the "Enter Hex Value" field on this tool.
4. After converting to JSON, make your desired changes to the JSON object.
5. Convert the updated JSON back to Hex and copy the Hex string.
6. Paste the Hex string back into RedisInsight to update the value.

## Running Locally

To run this tool locally, simply open the HTML file in a web browser. No server setup is required, and all processing is done client-side for privacy and convenience.

## Dependencies

- [Tailwind CSS](https://tailwindcss.com/) for styling.
- [msgpack-lite](https://github.com/kawanet/msgpack-lite) for encoding and decoding MessagePack data.

## License

This project is open-source and available under the MIT License.
