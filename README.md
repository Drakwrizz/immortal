# immortal

## Description
This is a binary file that when executed, cannot be removed from the computer before a reboot.<br />
It has no other goal than that.<br />
If you find a way to remove it feel free to post a github issue.<br />
It currently only work on linux machine.<br />

## How does it work
The code takes the binary file and monitors it. <br />
If the binary file is removed, a process rebuilds it. <br />
This process is totally unkillable regardless of the user's permission. <br />
This file does not require any permission to be executed or run.<br /> 

## Why a binary and not the source code ?
This code was created as a fun side project. <br /> 
I condone any use of my code in creating viruses; however, I find this code to be still interesting as it stands.<br /> 
That's why I'm providing this code as a binary file - to make it more difficult for anyone with malicious intent to modify it.

## Running the code

To get the code running you can follow these simple example steps.<br /> 
1. Clone the repo
  ```sh
  git clone https://github.com/Drakwrizz/immortal 
  ```
2. Make the file executable
  ```sh
  cd chmod +x immortal/immortal
  ```
3. Run the code
  ```sh
  immortal/immortal
  ```

## Contributing
If you want to contribute, you can post a github issue with a way you found to remove the file.

