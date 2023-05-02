# awx-sa

Playbooky pro AWX ke kontrole prostredi SA APIM.


## Popis instalace - draft

Azure VMs mají tagy. Na základě toho tagu je pak dynamický inventory přiřazuje
do odpovídající ansible group. Na tuto group se pak implementují další playbooky

Propojení AWX - azure je na základě service principalu, který musí existovat a
musí mít odpovídající oprávnění, aby mohl v dané resource-group vytvářet
resources. 


