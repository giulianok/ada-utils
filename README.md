# ada-utils
Many util javascript algorithms for accessibility


## Navigation
Requires arrow navigation.
> Left and Right for move between the links
> Up and Down to toggle submenus

### Model:
menu | menubar > munuitem
menu | menubar > button
nav > menuitem

### Submenus
Trigger needs:
> aria-expanded="true | false"
> aria-haspopup= "true"
> aria-controls = "id of target"
> aria-owns = "id of target"

Target needs:
> ID


## Images 
Need an title and alt tag