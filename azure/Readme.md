az vmss list-instances --resource-group rg-XXX --name vmss-XXX

az vmss update-instances --instance-ids 2  --resource-group rg-XXX --name vmss-XXX

az vmss scale --new-capacity 2  --resource-group rg-XXX --name vmss-XXX
