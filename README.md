# s3si.ts
## This version of s3si.ts is designed to be used with Splashcat running locally on your computer.


Export your battles from SplatNet to stat.ink and Splashcat.

If you have used s3s, please see [here](#migrate-from-s3s).

## Usage

1. Install [deno](https://deno.land/)

2. Make sure you have Splashcat running on http://127.0.0.1:8000 and have followed these steps

3. Run
   `deno run -Ar https://raw.githubusercontent.com/bentheminernz/s3si.ts-local-splashcat/main/s3si.ts -e splashcat`

4. If it's your first time running this, follow the instructions to login to
   Nintendo Account. Your token will be saved to `profile.json` for future use.

- If you want to use a different profile, use `-p` to specify the path to the
  profile file.


### Other s3si.ts documentation
For the rest of the s3si.ts documentation go [here](https://github.com/spacemeowx2/s3si.ts/blob/main/README.md)

### Splashcat Notes
Due to limitations with SplatNet 3 data, Splashcat requires battles uploaded to
use `en-US` (set with `userLang`). Splashcat will localize most parts of battle
results into the user's language when displayed.

## Credits

- https://github.com/frozenpandaman/s3s
- https://github.com/fetus-hina/stat.ink
- https://github.com/splashcat-ink/splashcat
