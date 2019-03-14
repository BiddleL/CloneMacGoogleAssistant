# MacAssistant

A project that integrates the Google Assistant into macOS, using the Google Assistant SDK. Cloned in order to create a personalised version

MacAssistant can bring that number to 200 million

![](images/1.png)
![](images/2.png)
![](images/3.png)

## Download
Downloads are listed under the `Releases` tab.
Click [here](https://github.com/vanshg/MacAssistant/releases/download/0.2/MacAssistant.zip) to directly download the latest version.

MacAssistant is currently in Beta.

## Example Queries
*"What's the weather today?"*

*"My agenda for tomorrow."*

*"When was Benedict Cumberbatch born?*"

*"Does the president of the United States have any children?"*

## Build Instructions
MacAssistant is built using Swift 4 and Xcode 9.1

Clone the project using `git clone --recursive https://github.com/vanshg/MacAssistant.git` (This project relies on some submodules to work)

Once cloned, `cd` into the `grpc-swift` directory, and run `make`.

You should then be able to open the `MacAssistant.xcworkspace` file (not `xcproject`!)

You will also need OAuth credentials from the [Google Developer Console](https://console.developers.google.com). In order to get them, you'll need to create a new project and enable the Assistant API for that project. Then, generate an OAuth credential, and select application type of `Other`. Download the json file by clicking the button on the right. Finally, rename the file to `google_oauth.json` and place it in your project (*/MacAssistant/google_oauth.json*).

## Contributing
Please feel free to contribute to this project. I welcome all contributions and pull requests. There is a list of pending things that need to be worked on in the [TODO](TODO.md) file.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
