# Script to Provisioning ONU Huawei

1. enable
2. configure
3. interface gpon 0/[portaslotid]
4. ont add [portaid] sn-auth [serial] omci ont-lineprofile-id [ID] ont-srvprofile-id [ID] desc "[nomeCliente]"
5. ont port native-vlan [portaid] [onuID] eth 1 vlan [ VLAND ID]
6. ont port native-vlan [portaid] [onuID] eth 2 vlan [VLAN ID]
7. quit
8. service-port [servicoPortaID] vlan [VLAN ID] gpon 0/[portaslotid]/[portaid] ont [onuID] gemport [GEM ID] multi-service user-vlan [VLAN ID] tag-transform translate

# Credits

> VirteX Telecom
