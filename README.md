# GoEssential integration for Neos CMS

With GoEssential you can bring all your videos to your website and excite your visitors with
essentialized videos.

## Installation

Add the dependency to your site package like this

    composer require goe/neos-package --no-update 
    
And then run `composer update` in your projects root folder.

## Usage

The package introduces a new content element called `GoE.Neos:Content.Library`:

![Preview in the Neos demo site](Documentation/goe-neos-creation-dialog.png) 

Once you have created a new content element you have to set your GoEssential organisation identifier in the inspector panel:
![Preview in the Neos demo site](Documentation/goe-neos-inspector.png) 

Your GoEssential video library is now ready for publishing:
![Preview in the Neos demo site](Documentation/goe-neos-example.png)

## Acknowledgment
https://goessential.com/

## License
The MIT License (MIT). Please see [LICENSE](LICENSE) for more information.




