# [Command] _network manager security-admin-config rule-collection delete_

Delete an admin rule collection.

## Versions

### [2022-01-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL25ldHdvcmttYW5hZ2Vycy97fS9zZWN1cml0eWFkbWluY29uZmlndXJhdGlvbnMve30vcnVsZWNvbGxlY3Rpb25zL3t9/2022-01-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/networkmanagers/{}/securityadminconfigurations/{}/rulecollections/{} 2022-01-01 -->

#### examples

- Delete an admin rule collection.
    ```bash
        network manager security-admin-config rule-collection delete --configuration-name "myTestSecurityConfig" --network-manager-name "testNetworkManager" --resource-group "rg1" --rule-collection-name "myTestCollection"
    ```

### [2024-01-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL25ldHdvcmttYW5hZ2Vycy97fS9zZWN1cml0eWFkbWluY29uZmlndXJhdGlvbnMve30vcnVsZWNvbGxlY3Rpb25zL3t9/2024-01-01-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/networkmanagers/{}/securityadminconfigurations/{}/rulecollections/{} 2024-01-01-preview -->

#### examples

- Delete an admin rule collection.
    ```bash
        network manager security-admin-config rule-collection delete --configuration-name "myTestSecurityConfig" --network-manager-name "testNetworkManager" --resource-group "rg1" --rule-collection-name "myTestCollection"
    ```
