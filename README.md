# GrabFood's Trademark Logo 1200x1200 | (Holloway) Chew, Kean Ho's Creative Visuals

[![logo](/share/icons/chewkeanho/trademarks/grabfood_1200x1200.svg)](#)

The GrabFood's Trademark Logo. They published clear trademark guideline and
supplied the required but incompatible material files for it. The preferred
version is `.svg` which has non-destructive scale up & down properties and can
be converted into any rasterized images (e.g. `jpeg`, `webp`, `avif`, etc). To
comply with our standards, a re-draw is required.

This project re-draws GrabFood's Trademark Logo specifically for 1200x1200 size.




## Verifying Content Integrity

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

To secure the content from unauthorized modification by anyone down to bit-level
(`0|1`), they are cryptographically signed using one or more cryptography tools
such as but not limited to:

* [GnuPG](https://gnupg.org); AND/OR
* [OpenSSL](https://www.openssl.org/).

The public key and the associated certificate are attached. Only the main owner
keeps and maintains the private keys. To verify the content's integrity:



### GnuPG

1. Install [GnuPG](https://gnupg.org) software if not present.
2. Download the target file and its detached signature file (the `.asc` file
   with the same filename).
3. Download the public key file (`.gpg`).
4. Place them next to each other in the directory.
5. Open a terminal and execute the following command:

```
$ gpg --no-default-keyring --keyring /path/to/public.gpg --verify /path/to/file.asc
```



### OpenSSL

1. Install [OpenSSL](https://www.openssl.org) software if not present.
2. Download the target file and its detached signature file (the `.sig`/`.sign`
   file with the same filename).
3. Download the public certificate file (`.pem`) containing the public key
   within.
4. Place them next to each other in the directory.
5. Open a terminal and execute the following command:

```
$ openssl dgst -verify /path/to/pubkey.pem -signature /path/to/file.sig /path/to/file
```




## Artificial Intelligence (A.I.) Decrees

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

Please refer to [AI_DECREES.md](AI_DECREES.md) for the project's policy on the
use of Artificial Intelligence.




## Trademark Registry

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

Please refer to [TRADEMARKS.txt](TRADEMARKS.txt) for the registered trademark's
information.




## References

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

Please refer to [REFERENCES.md](REFERENCES.md) for the project's references.




## Maintainers' Notes

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

1. Please refer to [CONTRIBUTING.md](CONTRIBUTING.md) for contributing &
   maintenances guidelines.
2. Since Grab published its trademark guidelines, you **MUST** go through the
   following specifications to avoid any unwanted legal implications:
   * https://merchant.grab.com/en-my/brand-centre/grabfood
   * Standard Global Trademark Laws
   * Local Trademark Laws
3. For repository trademarks' ownership, this repo uses the `TRADEMARKS.txt` for
   tracking the trademarks' owners.
     1. The file has its internal guides as comments. Please comply accordingly.
     2. As trademarks are renewable across time, please check with the owners
        and update this file at least annually.
4. While not specified by Grab; please ensures the outputs are web-ready. Refer:
   * https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/How_to/Define_app_icons
   * https://web.dev/articles/maskable-icon
   * https://developer.x.com/en/docs/x-for-websites/cards/overview/summary-card-with-large-image
   * https://developers.facebook.com/docs/sharing/webmasters/images/
5. For directory organizations:
   * The principal canvas **MUST BE SAVED** in `inkscape SVG format` and retain
     all legal attributes (license, copyright, etc). The files **MUST HAVE**
     `inkscape-` prefixes to avoid confusion. They are saved inside
     `/share/icons/[PROJECT]/principal-canvas` directory.
   * The exported svg **MUST BE IN** `Plain SVG format` and retain all legal
     attributes (license, copright, etc). The files **MUST NOT HAVE**
     `inkscape-` prefixes. They are saved inside `/share/icons/[PROJECT]/`
     directory.
   * The main-course **MUST** always be `.svg` as end-user can use GIMP to
     convert into other formats.
   * Therefore, additional non-text based images (e.g. `.ico`, `.jpg`, `.webp`,
     and `.avif`) should be published in `Release` section as "Good to Have"
     convenient side-dishes.




## License

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

* [Agreed GIMP License](.internals/terms-of-services/GimpORG-License.pdf)
* [Agreed GIMP Privacy Policy](.internals/privacy-policy/GimpORG-Privacy-Policy.pdf)
* [Agreed Inkscape License](.internals/terms-of-services/Inkscape-License.pdf)
* [Agreed Inkscape Privacy Policy](.internals/privacy-policy/Inkscape-Privacy-Policy.pdf)

This entire repository is licensed under
[Creative Commons Attribution-NoDerivatives 4.0 International License](LICENSE.txt).
To ensure better understanding of this license, the following sub-sections will
briefly describe how to deploy the content.

For registered non-profit organizations (NGO), you are considered a
`Commercial Entity` the same as any for-profit organization by default. However,
you will be eligible for the NGO disbursement grant and receive exception
privileges from the creator(s).

> [!CAUTION]
>
> While the images are licensed under a Creative Commons (CC) license, **YOU ARE
> STILL OBLIGATED TO COMPLY WITH GRABFOOD'S TRADEMARK REQUIREMENTS
> (refer: https://merchant.grab.com/en-my/brand-centre/grabfood)**.
>
> In any case, use the material files as provided. **DO NOT MODIFY THEM UNDER
> ANY CIRCUMSTANCES**.



### Attribution

Unless otherwise specified in writing, you **MUST** attribute back to the
creator(s) as follows:

```
Title: GrabFood's Trademark Logo 1200x1200
Creators: Grab
Packaged-By: (Holloway) Chew, Kean Ho
Contact: hello@chewkeanho.com
SKU: chewkeanho-visuals-trademarks-grabfood-1200x1200
UUID: 9E9C1E5F-95BC-4D90-BE81-2F7C767E39E6
License: Creative Commons Attribution-NoDerivatives 4.0 International License (https://creativecommons.org/licenses/by-nd/4.0)
Repository Made On: 2026-02-03
Repository Made From: Malaysia, South East Asia
Procure: https://github.com/ChewKeanHo/visuals-trademarks-grabfood-1200x1200
```



### Ownership - Personal

> [!NOTE]
>
> This targets any customer wanting to own a copy of the content and then only
> he/she is using it without sharing with any 3rd-party entity; AND **WITHOUT**
> any monetary intention such as but not limited to:
>
> * Saving a local copy and then viewing via his/her own mobile device(s); OR
> * Saving a local copy and then viewing via his/her own personal computer; OR
> * Saving a local copy for artificial intelligence data training purposes.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
attribution.



### Ownership - Commercial

> [!NOTE]
>
> This targets any customer wanting to own a copy of the content and then only
> he/she is using it without sharing with any 3rd-party entity; AND **WITH** any
> monetary intention such as but not limited to:
>
> * Saving a local copy for enhancing his/her company's procurement list; OR
> * Saving a local copy for commercial artificial intelligence data training
>   purposes.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
attribution.



### Reference - Personal & Commercial

> [!NOTE]
>
> This targets any customer wanting to refer or to provide a guide for sourcing
> the original content for any 3rd-party entity **without directly displaying
> any portion of the original content**; **WITHOUT** any monetary intention such
> as but not limited to:
>
> * Academic research and paper writing; OR
> * New content creation linking to the original content **WITHOUT displaying
>   any of the original content** for his/her own streaming platform; OR
> * Content production and collection linking to original content **WITHOUT
>   displaying any of the original content**; OR
> * Web portfolio project linking to the original content **WITHOUT displaying
>   any of the original content**; OR
> * Event materials linking the original content **WITHOUT displaying any of the
>   original content**; OR
> * Meeting materials linking the original content **WITHOUT displaying any of
>   the original content**; OR
> * Advertisement contents linking the original content **WITHOUT displaying any
>   of the original content**.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
attribution.



### Integration - Personal

> [!NOTE]
>
> This targets any customer wanting to directly **display portions and NOT ALL**
> of the original content **as it is OR without any composing remixes or
> modifications retaining the original intent, art direction and messages** into
> his/her content creation; **WITHOUT** any monetary intention such as but not
> limited to:
>
> * New content creation with displaying portion(s) of the original content for
>   his/her own streaming platform **without any monetary gain**; OR
> * Content production and collection with displaying portion(s) of the original
>   content **without any monetary gain**; OR
> * Web portfolio project with displaying portion(s) of the original content
>   **without any monetary gain**; OR
> * Event materials with displaying portion(s) of the original content
>   **without any monetary gain**; OR
> * Meeting materials with displaying portion(s) of the original content
>   **without any monetary gain**.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
attribution.



### Integration - Commercial

> [!NOTE]
>
> This targets any customer wanting to directly **display portions and NOT ALL**
> of the original content **as it is OR without any composing remixes or
> modifications retaining the original intent, art direction and messages** into
> his/her content creation; **WITH** any monetary intention such as but not
> limited to:
>
> * New content creation with displaying portion(s) of the original content for
>   his/her own streaming platform; OR
> * Content production and collection with displaying portion(s) of the original
>   content; OR
> * Web portfolio project with displaying portion(s) of the original content; OR
> * Event materials with displaying portion(s) of the original content; OR
> * Meeting materials with displaying portion(s) of the original content; OR
> * Advertisement materials with displaying portion(s) of the original content.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
attribution.



### Composition Remix - Personal

> [!NOTE]
>
> This targets any customer wanting to own and then **modify the original
> content extensively preserving or altering the original intent, art direction,
> or message** for composing his/her new content creation; **WITHOUT** any
> monetary intention such as but not limited to:
>
> * New content creation with digitally modified and processed original content
>   integration for his/her own streaming platform **WITHOUT** any profits
>   including advertisement commission; OR
> * Personal content production and collection with digitally modified and
>   processed original content integration for his/her own streaming platform
>   **WITHOUT** any profits including advertisement commission; OR
> * Personal web portfolio project with digitally modified and processed
>   original content integration for his/her own streaming platform **WITHOUT**
>   any profits including advertisement commission; OR
> * Social media meme content creation with digitally modified and processed
>   original content integration for his/her own streaming platform **WITHOUT**
>   any profits including advertisement commission.

You are **NOT ALLOWED** due to the license restriction.



### Composition Remix - Commercial

> [!NOTE]
>
> This targets any customer wanting to own and then **modify the original
> content extensively preserving or altering the original intent, art direction,
> or message** for composing his/her new content creation; **WITH** any monetary
> intention such as but not limited to:
>
> * New content creation with digitally modified and processed original content
>   integration for his/her own streaming platform; OR
> * Personal content production and collection with digitally modified and
>   processed original content integration for his/her own streaming platform;
>   OR
> * Personal web portfolio project with digitally modified and processed
>   original content integration for his/her own streaming platform; OR
> * Social media meme content creation with digitally modified and processed
>   original content integration for his/her own streaming platform.

You are **NOT ALLOWED** due to the license restriction.



### Broadcast or Resell Redistribution - Personal

> [!NOTE]
>
> This targets any customer wanting to share, to broadcast, to re-distribute,
> to sell, or to re-sell the original, **modified, OR derived** content
> **WITHOUT** any monetary intention such as but not limited to:
>
> * Sharing with family members; OR
> * Streaming the content via any streaming platform with private viewer
>   access; OR
> * Displaying the content in his/her gallery with privately invited guests; OR
> * Displaying the content in private, free entry open spaces like living room;
>   OR
> * Owning a copy of the original content and serving it as downloadable content
>   on a website in a private network (e.g. self-hosted home network); OR
> * Sharing the original content across social media or messaging applications
>   like email or instant messenger.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
attribution.



### Broadcast or Resell Redistribution - Commercial

> [!NOTE]
>
> This targets any customer wanting to share, to broadcast, to re-distribute,
> to sell, or to re-sell the original, **modified, OR derived** content
> **WITH** any monetary intention such as but not limited to:
>
> * Streaming the content via any streaming platform with public or private
>   viewer access; OR
> * Displaying the content in any company's public events with free or payable
>   guest invites; OR
> * Displaying the content in any company's internal/private events with free or
>   payable guest invites; OR
> * Owning a copy of the original content and serving it as free OR payable
>   downloadable content on his/her website in any network (Internet, Intranet,
>   or private networks); OR
> * Sharing the original content across social media or messaging applications
>   like email or instant messenger; OR
> * Distributing the original content via multiple profit-earning streaming
>   platforms.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
attribution.
