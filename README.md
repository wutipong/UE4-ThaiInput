# UE4-ThaiInput
Temporary fix for Unreal Engine 4 which does not display Thai text properly in its editor's fields.

## How to use
1. Download the DroidSansFallback.ttf
2. Replace the file in *<UE4 directory>\Engine\Content\Slate\Fonts* with the downloaded file. Make backup where necessary.
3. Start the engine.
  
## Technical Details
UE4 uses DroidSansFallback font in the case that the chracter is not supported by any font it is currenly using. Since non of the fonts shipped with UE4 supports Thai, a 'Tofu' is displayed instead of proper Thai character.

The font file provided in this reprository is basically a merge between DroidSansFallback.ttf and DroidSansThai.ttf. Both of them are licensed under Apache License. This is aimed to provide support for Thai character set to DroidSansFallback font. 

Droid font family's digitized data copyright Google(c) 2009.
