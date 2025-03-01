---

copyright:
  years: 2019, 2021
lastupdated: "2021-04-26"

keywords: terraform resources, terraform modules, terraform provider, terraform autodeploy, 

subcollection: ibm-cloud-provider-for-terraform

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:codeblock: .codeblock}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:deprecated: .deprecated}
{:download: .download}
{:preview: .preview}

# What's new in Terraform on {{site.data.keyword.cloud_notm}}?
{: #new-in-terraform}

Learn about the latest changes to the Terraform on {{site.data.keyword.cloud_notm}} service that are grouped by month.

## 26 April 2021
{: #26-april-2021}

<table>
    <thead>
    <th style="width:80px">New resources</th>
    <th style="width:80px">New data sources</th>
    <th style="width:500px">Enhancements</th>
    </thead>
  <tbody>
    <tr>
 <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">NA</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">NA</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">Support `gateway_connection` attribute [ibm_is_vpn_gateway_connection](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#vpn-gateway-connection-output) resource</li><li style="margin:0px; padding:0px">Support additional attributes for [ibm_is_subnet_reserved_ip](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#subnet-reserved-ip-output) resource</li><li style="margin:0px; padding:0px">Added [ibm_iam_account_settings](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-iam-data-sources#iam-account-settings-dssample) data source example</li><li style="margin:0px; padding:0px">Support `resource_group_id` argument in [ibm_satellite_location](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-satellite-resources#satellite-location-input) resources and attribute in [ibm_satellite_location](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-satellite-data-sources#satellite-location-dsoutput) data source</li><li style="margin:0px; padding:0px">Support `ca-tor` region in [ibm_cos_bucket](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-object-storage-resources#hpvs-cos-bucket-input) resource.</li><li style="margin:0px; padding:0px">Support `private_address` attributes for [ibm_is_vpn_gateway](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#vpn-gateway-output) resource and [ibm_is_vpn_gateway](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#vpn-gateway-output) data source</li><li style="margin:0px; padding:0px">Support for `retention policy` argument in [ibm_cos_bucket](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-object-storage-resources#hpvs-cos-bucket-input) bucket and attribute in [`ibm_cos_bucket`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-object-storage-data-sources#cos-bucket-output) bucket</li><li style="margin:0px; padding:0px">Latest [version1.23.2 change log](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-provider-changelog#changelog-v1232) and [version1.23.1 change log](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-provider-changelog#changelog-v1231)</li></ul></td>
    </tr>
  </tbody>
  </table> 

## 4 April 2021
{: #4-april-2021}

<table>
    <thead>
    <th style="width:80px">New resources</th>
    <th style="width:80px">New data sources</th>
    <th style="width:500px">Enhancements</th>
    </thead>
  <tbody>
    <tr>
 <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">[`ibm_iam_account_settings`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-iam-resources#iam-account-settings)</li><li style="margin:0px; padding:0px">[`ibm_cm_catalog`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cm-resources#cm-catalog)</li><li style="margin:0px; padding:0px">[`ibm_cm_offering`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cm-resources#cm-offering)</li><li style="margin:0px; padding:0px">[`ibm_cm_offering_instance`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cm-resources#cm-offering-instance)</li><li style="margin:0px; padding:0px">[`ibm_cm_version`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cm-resources#cm-version)</li><li style="margin:0px; padding:0px">[`ibm_enterprise`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-enterprise-mgt-resources#enterprise)</li><li style="margin:0px; padding:0px">[`ibm_enterprise_account`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-enterprise-mgt-resources#enterprise-account)</li><li style="margin:0px; padding:0px">[`ibm_enterprise_account_group`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-enterprise-mgt-resources#enterprise-account-grp)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">[`ibm_iam_account_settings`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-iam-data-sources#iam-account-settings-ds)</li><li style="margin:0px; padding:0px">[`ibm_cm_catalog`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cm-data-sources#cm-catalog-ds)</li><li style="margin:0px; padding:0px">[`ibm_cm_offering`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cm-data-sources#cm-offering-ds)</li><li style="margin:0px; padding:0px">[`ibm_cm_offering_instance`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cm-data-sources#cm-offering-instanceds)</li><li style="margin:0px; padding:0px">[`ibm_cm_version`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cm-data-sources#cm-versionds)</li><li style="margin:0px; padding:0px">[`ibm_enterprises`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-enterprise-mgt-ds#enterprises-ds)</li><li style="margin:0px; padding:0px">[`ibm_enterprise_accounts`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-enterprise-mgt-ds#enterprise-accounts)</li><li style="margin:0px; padding:0px">[`ibm_enterprise_account_groups`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-enterprise-mgt-ds#enterprise-account-grps-ds)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">Latest [version change log](https://github.com/IBM-Cloud/terraform-provider-ibm/releases/tag/v1.23.0)</li></ul></td>
    </tr>
  </tbody>
  </table> 


## 1 April 2021
{: #1-april-2021}

<table>
    <thead>
    <th style="width:80px">New resources</th>
    <th style="width:80px">New data sources</th>
    <th style="width:500px">Enhancements</th>
    </thead>
  <tbody>
    <tr>
 <td><ul style="margin:0px 0px 0px 20px; padding:0px"> <li style="margin:0px; padding:0px">[`ibm_is_dedicated_host`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#is-dedicatedhost
)</li><li style="margin:0px; padding:0px">[`ibm_is_dedicated_host_group`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#is-dedicatedhost-group)</li><li style="margin:0px; padding:0px">[`ibm_is_subnet_reserved_ip`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#subnet-reserved-ip)</li><li style="margin:0px; padding:0px">[`ibm_kms_key_alias`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-kms-resources#kms-key-alias)</li><li style="margin:0px; padding:0px">[`ibm_kms_key_rings`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-kms-resources#kms-key-rings)</li><li style="margin:0px; padding:0px">[`ibm_ob_logging`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#observability-logging)</li><li style="margin:0px; padding:0px">[`ibm_ob_monitoring`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#observability-monitoring)</li><li style="margin:0px; padding:0px">[`ibm_pn_application_chrome`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-pn-resources#is-pn-appln-chrome)</li><li style="margin:0px; padding:0px">[`ibm_satellite_host`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-satellite-resources#satellite-host-resource))</li><li style="margin:0px; padding:0px">[`ibm_satellite_location`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-satellite-resources#satellite-location-resource)</li><li style="margin:0px; padding:0px">[`ibm_schematics_action`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-schematics-resources#schematics-action)</li><li style="margin:0px; padding:0px">[`ibm_schematics_job`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-schematics-resources#schematics-job)</li><li style="margin:0px; padding:0px">[`ibm_schematics_workspace`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-schematics-resources#schematics-wks)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">[`ibm_cis_cache_settings`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis_data#cis-cache-settings)</li><li style="margin:0px; padding:0px">[`ibm_is_dedicated_host`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources)</li><li style="margin:0px; padding:0px">[`ibm_is_dedicated_hosts`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#dedicated-hosts-ds)</li><li style="margin:0px; padding:0px">[`ibm_is_dedicated_host_group`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#dedicated-host-grp-ds)</li><li style="margin:0px; padding:0px">[`ibm_is_dedicated_host_groups`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#dedicated-host-grps-ds
)</li><li style="margin:0px; padding:0px">[`ibm_is_dedicated_host_profile`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#dedicated-host-profile-ds)</li><li style="margin:0px; padding:0px">[`ibm_kms_key_rings`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-kms-data-sources#kp-key-rings)</li><li style="margin:0px; padding:0px">[`ibm_pn_application_chrome`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-pn-data-sources)</li><li style="margin:0px; padding:0px">[`ibm_secrets_manager_secret`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-secrets-mgr-data-sources#secrets-mgr-secret-ds)</li><li style="margin:0px; padding:0px">[`ibm_secrets_manager_secrets`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-secrets-mgr-data-sources#secrets-mgr-secrets-ds)</li><li style="margin:0px; padding:0px">[`ibm_satellite_host`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-satellite-data-sources#satellite-host-ds)</li><li style="margin:0px; padding:0px">[`ibm_satellite_location`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-satellite-data-sources#satellite-location-ds)</li><li style="margin:0px; padding:0px">[`ibm_is_subnet_reserved_ip`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-subnet-reserved-ipds)</li><li style="margin:0px; padding:0px">[`ibm_is_subnet_reserved_ips`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-subnet-reserved-ipsds)</li><li style="margin:0px; padding:0px">[`ibm_schematics_action`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-schematics-data-sources#schematics-actionds)</li><li style="margin:0px; padding:0px">[`ibm_schematics_job`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-schematics-data-sources#schematics-jobds)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">Support `dh_group`, `key_lifetime`, and `authentication_algorithm` argument for [ibm_is_ipsec_policy](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#provider-ipsec), [ibm_is_ike_policy](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#provider-ike-policy) resources</li><li style="margin:0px; padding:0px">Support `delegate_vpc` argument for [ibm_is_vpc_routing_table_route](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#vpc-routing-table) resources</li><li style="margin:0px; padding:0px">Support `tags` argument for [ibm_is_security_group](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#sec-group) resources</li><li style="margin:0px; padding:0px">Support `security-groups` argument for [ibm_is_lb](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#lb) resources and [ibm_is_lb](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#ibm-is-lb) data sources</li><li style="margin:0px; padding:0px">Support `public_key` argument for [ibm_is_ssh_key](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-ssh-key) data sources</li><li style="margin:0px; padding:0px">Support `default_network_acl_name`, `default_security_group_name`, `default_routing_table_name` argument for [ibm_is_vpc](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#provider-vps) resources</li><li style="margin:0px; padding:0px">Support `quote_id` argument for [ibm_compute_vm_instance](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-infrastructure-resources#vm) resources</li><li style="margin:0px; padding:0px">Support `serve_stale_content` argument for [ibm_cis_cache_settings](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-cache) resources</li><li style="margin:0px; padding:0px">Support `alias`, `key_ring_id` argument for [ibm_kms_key](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-kms-resources#kms-key) resources and `aliases` attribute for [ibm_kms_key](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-kms-data-sources#kms-key-ds) and [ibm_kms_keys](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-kms-data-sources#kms-keys-ds)</li>  <li style="margin:0px; padding:0px">Support `visibility` argument for [{{site.data.keyword.terraform-provider_full_notm}}](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-provider-reference#provider-parameter-ov) and deprecated `generation` argument for [{{site.data.keyword.terraform-provider_full_notm}}](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-provider-reference#provider-parameter-ov)</li><li style="margin:0px; padding:0px">Updated `kind = "nodejs:10"`, in example for [ibm_function_action](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-function-resources#fn-action) resources and [ibm_function_rule](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-function-resources#fn-rule)</li><li style="margin:0px; padding:0px">Latest [version change log](https://github.com/IBM-Cloud/terraform-provider-ibm/releases/tag/v1.22.0)</li></ul></td>
    </tr>
  </tbody>
  </table> 


## 16 March 2021
{: #16-march-2021}

<table>
    <thead>
    <th style="width:80px">New resources</th>
    <th style="width:80px">New data sources</th>
    <th style="width:500px">Enhancements</th>
    </thead>
  <tbody>
    <tr>
 <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">NA</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">NA</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">Support `logging` argument description for [ibm_is_lb](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#lb)</li><li style="margin:0px; padding:0px">Support `accept_proxy_protocol` argument for [ibm_is_lb_listener](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#lb-listener-input)</li><li style="margin:0px; padding:0px">Added resources timeouts and depreciated wait_time_minutes argument for [ibm_compute_vm_instance](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-infrastructure-resources#vm)</li><li style="margin:0px; padding:0px">Support `tags` argument for [ibm_is_subnet](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#subnet-input), [ibm_is_network_acl](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#network-acl-input)resource and [ibm_is_subnet](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-subnet-input) data source</li><li style="margin:0px; padding:0px">Support `iam_id` argument for [iam_service_id](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-iam-resources#iam-service-id-output) resource</li><li style="margin:0px; padding:0px">Added `checksum` attribute for [ibm_is_image](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-image-output), [ibm_is_images](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#output-parameters) data sources and for [ibm_is_image](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#image-output) resource</li><li style="margin:0px; padding:0px">Latest [version change log](https://github.com/IBM-Cloud/terraform-provider-ibm/releases/tag/v1.21.2)</li></ul></td>
    </tr>
  </tbody>
  </table> 


## 04 March 2021
{: #04-march-2021}

<table>
    <thead>
    <th style="width:80px">New resources</th>
    <th style="width:80px">New data sources</th>
    <th style="width:500px">Enhancements</th>
    </thead>
  <tbody>
    <tr>
 <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">NA</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">NA</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">Support `sort` argument for [ibm_iam_user_policy](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-iam-data-sources#iam-user-policy-input) and [ibm_iam_service_policy](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-iam-data-sources#iam-service-policy-input) data sources</li><li style="margin:0px; padding:0px">Support `default_routing_table` attribute for [ibm_is_vpc](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-output) data source and [ibm_is_vpc](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#vpc-arguments) resources.</li><li style="margin:0px; padding:0px">Support `logging` argument for [ibm_is_lb](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#lb-input)</li><li style="margin:0px; padding:0px">Updated `boot_volume` attributes for [ibm_is_instance_template](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#vpc-is-instance-template) resources</li><li style="margin:0px; padding:0px">Support `auto_delete_volume`  argument for [vpc generation 2](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#container-cluster-input)</li><li style="margin:0px; padding:0px">Support  `resource_group_id` argument for force new resource for [ibm_cis](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-input) and [ibm_database](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-databases-resources#db-input) resources</li><li style="margin:0px; padding:0px">Example update  and support `code_path` argument for [ibm_function_action](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-function-resources#fn-action-input) resources</li><li style="margin:0px; padding:0px">Latest [version change log](https://github.com/IBM-Cloud/terraform-provider-ibm/releases/tag/v1.21.1)</li></ul></td>
    </tr>
  </tbody>
  </table> 

## 17 February 2021
{: #17-february-2021}

<table>
    <thead>
    <th style="width:80px">New resources</th>
    <th style="width:80px">New data sources</th>
    <th style="width:500px">Enhancements</th>
    </thead>
  <tbody>
    <tr>
 <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">NA</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">[`ibm_pi_catalog_images`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-power-data-sources#pi-catalog-image)</li><li style="margin:0px; padding:0px">[`ibm_is_volume_profile`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#volume-profile-ds)</li><li style="margin:0px; padding:0px">[`ibm_is_volume_profiles`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#volume-profiles-ds)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">Support `lunid` argument for [ibm_storage_block](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-infrastructure-resources#storage-block-output) resource</li><li style="margin:0px; padding:0px">Support `auto_delete_volume` argument for [ibm_is_instance](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#instance-input) resource</li><li style="margin:0px; padding:0px">Support `wait_till` argument for [ibm_container_cluster resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#container-cluster-input)</li><li style="margin:0px; padding:0px">Support `patch_version` argument for [ibm_container_cluster](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#container-cluster-input), [ibm_container_vpc_cluster](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#vpc-cluster-input) resources, and [ibm_is_instance data source](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#instances) data source</li><li style="margin:0px; padding:0px">Support `auto_delete_volume`  argument for [vpc generation 2](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#container-cluster-input)</li><li style="margin:0px; padding:0px">Support `session_stickiness` attribute to enable `HTTP_COOKIE` for [ibm_lbass](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-infrastructure-resources#lbaas-input) resource </li><li style="margin:0px; padding:0px">Example update for [ibm_certificate_manager_order](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cert-manager-resources#certmanager-order-sample), [ibm_certificate_manager_import](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cert-manager-resources#cert-manager-sample), [ibm_resource_instance](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-resource-mgmt-resources#resource-instance-sample), and [ibm_resource_key](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-resource-mgmt-resources#resource-key-sample) resource</li><li style="margin:0px; padding:0px">Latest [version change log](https://github.com/IBM-Cloud/terraform-provider-ibm/releases/tag/v1.21.0)</li></ul></td>
    </tr>
  </tbody>
  </table> 


## 28 January 2021
{: #28-january-2021}

<table>
    <thead>
    <th style="width:80px">New resources</th>
    <th style="width:80px">New data sources</th>
    <th style="width:500px">Enhancements</th>
    </thead>
  <tbody>
    <tr>
 <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">[`ibm_dl_provider_gateway`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-dl-gateway-resource#dl-provider-gwy)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">[`ibm_dl_provider_gateways`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-dl-gateway-ds#dl-provider-gwy-ds)</li><li style="margin:0px; padding:0px">[`ibm_dl_provider_ports`](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-dl-gateway-ds#dl-provider-ports-ds)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">Support for `pod_subnet` and `service-subnet` arguments for [ibm_container_cluster resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#container-cluster-input)</li><li style="margin:0px; padding:0px">Support `vpc_name` and `vpc` arguments to filter the instances [ibm_is_instance data source](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#instances) </li><li style="margin:0px; padding:0px">Support `patch_version` argument for [ibm_container_cluster resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#container-cluster-input) and [ibm_container_vpc_cluster resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#vpc-cluster)</li><li style="margin:0px; padding:0px">Support `architecture` attribute for [vpc instance profile](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-instance-profile-input) and [vpc_instance_profiles](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-instance-profiles-input) data source</li><li style="margin:0px; padding:0px">Latest version change log for [IBM Cloud provider](https://github.com/IBM-Cloud/terraform-provider-ibm/releases/tag/v1.20.1)</li></ul></td>
    </tr>
  </tbody>
  </table>


## 13 January 2021
{: #13-january-2021}

<table>
    <thead>
    <th style="width:80px">New resources</th>
    <th style="width:80px">New data sources</th>
    <th style="width:500px">Enhancements</th>
    </thead>
  <tbody>
    <tr>
 <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">[ibm_container_api_key_reset](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#container-api-key-reset)</li><li style="margin:0px; padding:0px">[ibm_cr_namespace](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-registry#cr-namespace)</li><li style="margin:0px; padding:0px">[ibm_iam_service_api_key](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-iam-resources#iam-service-api-key)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">[ibm_cr_namespaces](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-registry-data-sources#cr-namespaces-ds)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">Support `api_key_id`, `api_key_owner_name`, and `api_key_owner_email` attributes for [ibm_container_cluster resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-data-sources#container-cluster-output)</li><li style="margin:0px; padding:0px">Support `crn` in target attribute for VPC virtual endpoint for [ibm_is_virtual_endpoint_gateway](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#virtual-endpoint-gwy-input)</li><li style="margin:0px; padding:0px">Updated an example for [ibm_container_addons resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#container-addons)</li><li style="margin:0px; padding:0px">Updated next-hop attribute as required for [ibm_is_vpc_route](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#vpc-route-input)</li><li style="margin:0px; padding:0px">Latest version change log for [IBM Cloud provider](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-provider-changelog#changelog-v1190)</li></ul></td>
    </tr>
  </tbody>
  </table>

  
## 29 December 2020
{: #29-december-2020}

<table>
    <thead>
    <th style="width:80px">New resources</th>
    <th style="width:80px">New data sources</th>
    <th style="width:500px">Enhancements</th>
    </thead>
  <tbody>
    <tr>
 <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">[ibm_cis_certificate_order](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-certificate-order)</li><li style="margin:0px; padding:0px">[ibm_cis_certificate_upload](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-certificate-upload)</li><li style="margin:0px; padding:0px">[ibm_cis_dns_records_import](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-dns-records-import)</li><li style="margin:0px; padding:0px">[ibm_cis_dns_record](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-dns-record)</li><li style="margin:0px; padding:0px">[ibm_cis_page_rule](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-page-rule)</li><li style="margin:0px; padding:0px">[ibm_is_virtual_endpoint_gateway](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#virtual-endpoint-gwy)</li><li style="margin:0px; padding:0px">[ibm_is_virtual_endpoint_gateway_ip](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#virtual-endpoint-gwyip)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">[ibm_cis_certificates](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis_data#cis-certificates)</li><li style="margin:0px; padding:0px">[ibm_cis_custom_certificates](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis_data#cis-custom-certificates)</li><li style="margin:0px; padding:0px">[ibm_cis_page_rules](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis_data#cis-page-rules)</li><li style="margin:0px; padding:0px">[ibm_cis_dns_record](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis_data#cis-dns-record
)</li><li style="margin:0px; padding:0px">[ibm_is_virtual_endpoint_gateways](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-endpoint-gwysds)</li><li style="margin:0px; padding:0px">[ibm_is_virtual_endpoint_gateway_ips](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-endpoint-gwy-ipsds)</li><li style="margin:0px; padding:0px">[ibm_is_virtual_endpoint_gateway](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-endpoint-gwyds)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">Status attribute for [ibm_container_alb_cert resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#container-alb-cert)</li><li style="margin:0px; padding:0px">Persistence and namespace attribute for [ibm_container_alb_cert resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#container-alb-cert)</li><li style="margin:0px; padding:0px">Labels argument for [ibm_container_cluster resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-resources#container-cluster)</li></ul></td>
    </tr>
  </tbody>
  </table>

## 14 December 2020
{: #14-december-2020}

<table>
    <thead>
    <th style="width:80px">New resources</th>
    <th style="width:80px">New data sources</th>
    <th style="width:500px">Enhancements</th>
    </thead>
  <tbody>
    <tr>
 <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">[ibm_cis_routing](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-routing)</li><li style="margin:0px; padding:0px">[ibm_cis_cache_settings](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-cache)<li style="margin:0px; padding:0px">[ibm_cis_custom_page](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-custom)<li style="margin:0px; padding:0px">[ibm_dns_glb](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-dns-resources#dns-glb)<li style="margin:0px; padding:0px">[ibm_dns_glb_monitor](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-dns-resources#dns-glb-monitor)<li style="margin:0px; padding:0px">[ibm_dns_glb_pool](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-dns-resources#dns-glb-pool)<li style="margin:0px; padding:0px">[ibm_is_vpc_routing_table](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#vpc-routing-table)<li style="margin:0px; padding:0px">[ibm_is_vpc_routing_table_route](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#vpc-routing-table-route)</li><li style="margin:0px; padding:0px">[ibm_cis_waf_rule](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-waf-rule)</li><li style="margin:0px; padding:0px">[ibm_cis_waf_package](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-waf-package)<li style="margin:0px; padding:0px">[ibm_cis_waf_group](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-waf-grp)</li><li style="margin:0px; padding:0px">[ibm_cis_range_app](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis_range_app)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">[ibm_cis_global_load_balancers](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis_data#cis-global-lb-ds)</li><li style="margin:0px; padding:0px">[ibm_cis_custom_pages](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis-resources#cis-custom)</li><li style="margin:0px; padding:0px">[ibm_dns_glbs](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-dns-data-sources#dns-glbs-ds)</li><li style="margin:0px; padding:0px">[ibm_dns_glb_monitors](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-dns-data-sources#dns-glb-monitors-ds)</li><li style="margin:0px; padding:0px">[ibm_dns_glb_pools](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-dns-data-sources#dns-glb-pools-ds)</li><li style="margin:0px; padding:0px">[ibm_is_vpc_default_routing_table](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-default-routing-tableds)</li><li style="margin:0px; padding:0px">[ibm_is_vpc_routing_tables](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-routing-tableds)</li><li style="margin:0px; padding:0px">[ibm_is_vpc_routing_table_routes](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-routing-tablesds)</li><li style="margin:0px; padding:0px">[ibm_cis_waf_rules](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis_data#cis-waf-rules)</li><li style="margin:0px; padding:0px">[ibm_cis_waf_packages](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis_data#cis-waf-packages)<li style="margin:0px; padding:0px">[ibm_cis_waf_groups](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis_data#cis-waf-groups)</li><li style="margin:0px; padding:0px">[ibm_cis_range_apps](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis_data#cis-range-apps)</li><li style="margin:0px; padding:0px">[ibm_is_vpn_gateways](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-gateways-ds)</li><li style="margin:0px; padding:0px">[ibm_is_vpn_gateway_connections](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-gateways-connection-ds)</li></ul></td>
      <td><ul style="margin:0px 0px 0px 20px; padding:0px"><li style="margin:0px; padding:0px">public_ip attribute for [power network resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-power-vsi#power-network)</li><li style="margin:0px; padding:0px">Policies attribute for [ibm_kms_key resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-kms-resources#kms-key)</li><li style="margin:0px; padding:0px">Number of invited users and invited users attribute for [ibm_iam_user_invite resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-iam-resources#iam-user-invite-output)</li><li style="margin:0px; padding:0px">Support HTTPS protocol for [ibm_is_lb_pool](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#lb-pool)</li><li style="margin:0px; padding:0px">Encrypted data key and encryption key argument for [image data source](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-data-sources#vpc-image)</li><li style="margin:0px; padding:0px"> Archive rule argument for [COS bucket resource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-object-storage-resources#cos-bucket)</li><li style="margin:0px; padding:0px">Policies for [ibm_kms_key and ibm_kms_keys data source](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-kms-data-sources)</li><li style="margin:0px; padding:0px">List bounded services argument for [ibm_container_cluster data source](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-container-data-sources#container-cluster)</li><li style="margin:0px; padding:0px">Access rule and UA rule argument for [internet service firewall resource and datasource](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-cis_data#cis-firewall-dsoutput)</li><li style="margin:0px; padding:0px">Allow ip spoofing argument for [ibm_is_instance](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#instance-input)</li><li style="margin:0px; padding:0px">Routing table and ip version argument for [ibm_is_subnet](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#subnet-input)</li><li style="margin:0px; padding:0px">Import for [floating IP resources](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#floating-ip-import)</li><li style="margin:0px; padding:0px">Import for [Ike policy resources](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#provider-ike-policy-import)</li><li style="margin:0px; padding:0px">Import for [images resources](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#image-import)</li><li style="margin:0px; padding:0px">Import for [volume resources](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#volume-import)<li style="margin:0px; padding:0px">Archive rule,expire rule,force delete for [COS bucket](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-object-storage-resources#hpvs-cos-bucket-input)</li><li style="margin:0px; padding:0px">Support profile argument for [is_lb](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#lb)</li><li style="margin:0px; padding:0px">Update protocol and connection limit argument for  [ibm_is_lb_listener](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#lb-listener)</li><li style="margin:0px; padding:0px">Update protocol and connection limit argument for  [ibm_is_lb_listener](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#lb-listener)</li><li style="margin:0px; padding:0px">Support mode argument and status, created_at, members attributes for [ibm_dl_gateway](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-dl-gateway-resource#dl-gwy-input)</li><li style="margin:0px; padding:0px">Update the arguments and attributes for [ibm_is_vpn_gateway_connection](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-vpc-gen2-resources#vpn-gateway-connection)</li></ul></td>
    </tr>
  </tbody>
  </table> 
  
