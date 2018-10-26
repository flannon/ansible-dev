Notes

 - https://itnext.io/create-a-host-inventory-in-a-minute-with-ansible-c7bf251166d9


    ansible localhost -m setup --tree facts.d/
    jq . facts.d/localhost
    pip install ansible-cmdb
    ansible-cmdb -t html_fancy_plit -p loc_js=1 facts.d/
    open cmdb/index.html


