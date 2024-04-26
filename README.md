Install earlier version of flipper: 
brew install --cask https://raw.githubusercontent.com/Homebrew/homebrew-cask/9e7ee07b408d14ad0d5d0ca579bc0d4f5171f394/Casks/f/flipper.rb

When including XmtpRust in the podfile flipper will connect like normal

When not included Flipper will not connect with an error like: TCP Conn 0x600003384460 SSLHandshake failed (18,446,744,073,709,541,809)

