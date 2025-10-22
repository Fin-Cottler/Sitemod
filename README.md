
           ___                                    ___           ___           ___                   
          /\__\                                  /\__\         /\  \         /\  \         _____    
         /:/ _/_       ___           ___        /:/ _/_       |::\  \       /::\  \       /::\  \   
        /:/ /\  \     /\__\         /\__\      /:/ /\__\      |:|:\  \     /:/\:\  \     /:/\:\  \  
       /:/ /::\  \   /:/__/        /:/  /     /:/ /:/ _/_   __|:|\:\  \   /:/  \:\  \   /:/  \:\__\ 
      /:/_/:/\:\__\ /::\  \       /:/__/     /:/_/:/ /\__\ /::::|_\:\__\ /:/__/ \:\__\ /:/__/ \:|__|
      \:\/:/ /:/  / \/\:\  \__   /::\  \     \:\/:/ /:/  / \:\~~\  \/__/ \:\  \ /:/  / \:\  \ /:/  /
       \::/ /:/  /   ~~\:\/\__\ /:/\:\  \     \::/_/:/  /   \:\  \        \:\  /:/  /   \:\  /:/  / 
        \/_/:/  /       \::/  / \/__\:\  \     \:\/:/  /     \:\  \        \:\/:/  /     \:\/:/  /  
          /:/  /        /:/  /       \:\__\     \::/  /       \:\__\        \::/  /       \::/  /   
          \/__/         \/__/         \/__/      \/__/         \/__/         \/__/         \/__/   


What is Sitemod?

    Sitemod is a CSS Libary that enables tags to be added to HTML element classlists which apply styling.

Importing Sitemod:

    import from the sitemod.css file
    <link rel="stylesheet" href="Sitemod/sitemod.css" media="screen">

Using Sitemod:

    All HTML is encased within a <div class="container"></div> element

    Within the container element, div elements are created.
    Tags are added to the classlist. 

    <div class="tag1 tag2 tag3..."></div>

Grid:

    row-12:
        - creates a row with 12 columns with margins

    row-16:
        - creates a row with 16 columns with margins

    col-n:
        - creates a column that fills up n column slots of its row container starting with the left-most available slot
        - columns withing a row should add to the total space within the row (or less):
            ex.
            <div class="row-12">
                <div class="col-1"></div>
                <div class="col-5"></div>
                <div class="col-2"></div>
                <div class="col-4"></div>
            </div>
            1+4+5+2 = 12
            
Elements:

    foreground:
        - creates a box that fills screen
        - fixed position
        - z-index 1

    midground:
        - creates a box that fills screen
        - fixed position
        - z-index 0

    background:
        - creates a box that fills screen
        - fixed position
        - z-index -1

Alignment Attributes:

    left:
        - aligns element left
        - aligns text left
        
    right:
        - aligns element right
        - aligns text right

    center:
        - aligns element center
        - aligns text center

Size Attributes:

    fit:
        - Child elements are resized to fit the bounds of parent element

    crop:
        - Parent element crops overflow of child elements

    stretch:
        - Element stretches image to fit its bounds
        - Overflowing text is denoted with an ellipsis

    smaller:
        - height = 5% screen height

    small:
        - height = 10% screen height

    large:
        - height = 20% screen height

    larger:
        - height = 50% screen height

    largest:
        - height = 100% screen height

    fill:
        - height = 100% parent element height

    fit-content:
        - Parent element resizes to fit content

Text Attributes:
    title 
        - Title text size

    header
        - Header text size

    subheader
        - Subheader text size

    body
        - Standard text size

    subscript
        - Subscript text size

    bold
        - Bolded text

    bolder
        - Extra bold text

    italic
        - Italicized text


Color Attributes:
    
    Listed below are tags to assign color to elements.
        - red
        - orange
        - yellow
        - lime
        - green
        - blue
        - purple
        - magenta
        - violet 
        - pink
        - white
        - black
        - transparent

    Listed below are tags to assign opacity to elements.
        - opacity-0
        - opacity-25
        - opacity-50
        - opacity-75
