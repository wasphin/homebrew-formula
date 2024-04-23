# homebrew-formula

## how to install

1. Clone this repo:
   ```sh
   git clone https://github.com/wasphin/homebrew-formula.git
   ```
1. Go to the repo dir and install:
   ```sh
   brew install --build-from-source ffmpeg.rb
   ```

## how to upgrade

1. Download the latest [ffmpeg.rb](https://raw.githubusercontent.com/Homebrew/homebrew-core/master/Formula/f/ffmpeg.rb) from upstream:
   ```sh
   rm -rf ffmpeg.rb && wget -c https://raw.githubusercontent.com/Homebrew/homebrew-core/master/Formula/f/ffmpeg.rb
   ```
1. Patch and update the formula file:
   ```sh
   git add -p ffmpeg.rb
   git checkout ffmpeg.rb
   ```
1. Build test:
   ```sh
   brew install --build-from-source ffmpeg.rb
   ```
1. Commit & push.
