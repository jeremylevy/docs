
---
title: "ManagedKubernetes"
block_external_search_index: true
---






## Create a ManagedKubernetes Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/cs/#ManagedKubernetes">ManagedKubernetes</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/cs/#ManagedKubernetesArgs">ManagedKubernetesArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">ManagedKubernetes</span><span class="p">(resource_name, opts=None, </span>addons=None<span class="p">, </span>availability_zone=None<span class="p">, </span>client_cert=None<span class="p">, </span>client_key=None<span class="p">, </span>cluster_ca_cert=None<span class="p">, </span>cpu_policy=None<span class="p">, </span>enable_ssh=None<span class="p">, </span>image_id=None<span class="p">, </span>install_cloud_monitor=None<span class="p">, </span>key_name=None<span class="p">, </span>kms_encrypted_password=None<span class="p">, </span>kms_encryption_context=None<span class="p">, </span>kube_config=None<span class="p">, </span>name=None<span class="p">, </span>name_prefix=None<span class="p">, </span>new_nat_gateway=None<span class="p">, </span>node_cidr_mask=None<span class="p">, </span>password=None<span class="p">, </span>pod_cidr=None<span class="p">, </span>pod_vswitch_ids=None<span class="p">, </span>proxy_mode=None<span class="p">, </span>service_cidr=None<span class="p">, </span>slb_internet_enabled=None<span class="p">, </span>user_ca=None<span class="p">, </span>version=None<span class="p">, </span>worker_auto_renew=None<span class="p">, </span>worker_auto_renew_period=None<span class="p">, </span>worker_data_disk_category=None<span class="p">, </span>worker_data_disk_size=None<span class="p">, </span>worker_disk_category=None<span class="p">, </span>worker_disk_size=None<span class="p">, </span>worker_instance_charge_type=None<span class="p">, </span>worker_instance_types=None<span class="p">, </span>worker_number=None<span class="p">, </span>worker_period=None<span class="p">, </span>worker_period_unit=None<span class="p">, </span>worker_vswitch_ids=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewManagedKubernetes<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/cs?tab=doc#ManagedKubernetesArgs">ManagedKubernetesArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/cs?tab=doc#ManagedKubernetes">ManagedKubernetes</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Cs.ManagedKubernetes.html">ManagedKubernetes</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.CS.ManagedKubernetesArgs.html">ManagedKubernetesArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

#### Resource Arguments




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Addons</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesaddon">List&lt;Managed<wbr>Kubernetes<wbr>Addon<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Availability<wbr>Zone</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Zone where new kubernetes cluster will be located. If it is not be specified, the `vswitch_ids` should be set, its value will be vswitch's zone.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Client<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of client certificate, like `~/.kube/client-cert.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Client<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of client key, like `~/.kube/client-key.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cluster<wbr>Ca<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of cluster ca certificate, like `~/.kube/cluster-ca-cert.pem`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}kubelet cpu policy. options: static|none. default: none.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Ssh</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Enable login to the node through SSH. default: false 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Custom Image support. Must based on CentOS7 or AliyunLinux2.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Install<wbr>Cloud<wbr>Monitor</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Install cloud monitor agent on ECS. default: true 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The keypair of ssh login cluster node, you have to create it first. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kms<wbr>Encrypted<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}An KMS encrypts password used to a cs kubernetes. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kms<wbr>Encryption<wbr>Context</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, object>?</span>
    </dt>
    <dd>{{% md %}}An KMS encryption context used to decrypt `kms_encrypted_password` before creating or updating a cs kubernetes with `kms_encrypted_password`. See [Encryption Context](https://www.alibabacloud.com/help/doc-detail/42975.htm). It is valid when `kms_encrypted_password` is set.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kube<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of kube config, like `~/.kube/config`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name<wbr>Prefix</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>New<wbr>Nat<wbr>Gateway</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to create a new nat gateway while creating kubernetes cluster. Default to true. Then openapi in Alibaba Cloud are not all on intranet, So turn this option on is a good choice.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Node<wbr>Cidr<wbr>Mask</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The node cidr block to specific how many pods can run on single node. 24-28 is allowed. 24 means 2^(32-24)-1=255 and the node can run at most 255 pods. default: 24
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password of ssh login cluster node. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pod<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}[Flannel Specific] The CIDR block for the pod network when using Flannel. 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pod<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}[Terway Specific] The vswitches for the pod network when using Terway.Be careful the `pod_vswitch_ids` can not equal to `worker_vswtich_ids`.but must be in same availability zones.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Proxy<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Proxy mode is option of kube-proxy. options: iptables|ipvs. default: ipvs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Service<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The CIDR block for the service network. It cannot be duplicated with the VPC CIDR and CIDR used by Kubernetes cluster in VPC, cannot be modified after creation.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Slb<wbr>Internet<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to create internet load balancer for API Server. Default to true.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>User<wbr>Ca</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of customized CA cert, you can use this CA to sign client certs to connect your cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Desired Kubernetes version. If you do not specify a value, the latest available version at resource creation is used and no upgrades will occur except you set a higher version number. The value must be configured and increased to upgrade the version when desired. Downgrades are not supported by ACK.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Auto<wbr>Renew</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Enable worker payment auto-renew, defaults to false.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Auto<wbr>Renew<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Worker payment auto-renew period. When period unit is `Month`, it can be one of {“1”, “2”, “3”, “6”, “12”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Data<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Data<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The system disk category of worker node. Its valid value are `cloud_ssd` and `cloud_efficiency`. Default to `cloud_efficiency`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The system disk size of worker node. Its valid value range [20~32768] in GB. Default to 20.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Instance<wbr>Charge<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Worker payment type. `PrePaid` or `PostPaid`, defaults to `PostPaid`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Worker<wbr>Instance<wbr>Types</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}The instance type of worker node. Specify one type for single AZ Cluster, three types for MultiAZ Cluster.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Worker<wbr>Number</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The worker node number of the kubernetes cluster. Default to 3. It is limited up to 50 and if you want to enlarge it, please apply white list or contact with us.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Worker payment period. When period unit is `Month`, it can be one of { “1”, “2”, “3”, “4”, “5”, “6”, “7”, “8”, “9”, “12”, “24”, “36”,”48”,”60”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”, “4”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Period<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Worker payment period unit. `Month` or `Week`, defaults to `Month`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Worker<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Addons</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesaddon">[]Managed<wbr>Kubernetes<wbr>Addon</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Availability<wbr>Zone</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Zone where new kubernetes cluster will be located. If it is not be specified, the `vswitch_ids` should be set, its value will be vswitch's zone.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Client<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of client certificate, like `~/.kube/client-cert.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Client<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of client key, like `~/.kube/client-key.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cluster<wbr>Ca<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of cluster ca certificate, like `~/.kube/cluster-ca-cert.pem`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}kubelet cpu policy. options: static|none. default: none.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Ssh</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Enable login to the node through SSH. default: false 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Custom Image support. Must based on CentOS7 or AliyunLinux2.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Install<wbr>Cloud<wbr>Monitor</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Install cloud monitor agent on ECS. default: true 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The keypair of ssh login cluster node, you have to create it first. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kms<wbr>Encrypted<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}An KMS encrypts password used to a cs kubernetes. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kms<wbr>Encryption<wbr>Context</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}An KMS encryption context used to decrypt `kms_encrypted_password` before creating or updating a cs kubernetes with `kms_encrypted_password`. See [Encryption Context](https://www.alibabacloud.com/help/doc-detail/42975.htm). It is valid when `kms_encrypted_password` is set.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kube<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of kube config, like `~/.kube/config`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name<wbr>Prefix</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>New<wbr>Nat<wbr>Gateway</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to create a new nat gateway while creating kubernetes cluster. Default to true. Then openapi in Alibaba Cloud are not all on intranet, So turn this option on is a good choice.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Node<wbr>Cidr<wbr>Mask</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The node cidr block to specific how many pods can run on single node. 24-28 is allowed. 24 means 2^(32-24)-1=255 and the node can run at most 255 pods. default: 24
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The password of ssh login cluster node. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pod<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}[Flannel Specific] The CIDR block for the pod network when using Flannel. 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pod<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}[Terway Specific] The vswitches for the pod network when using Terway.Be careful the `pod_vswitch_ids` can not equal to `worker_vswtich_ids`.but must be in same availability zones.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Proxy<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Proxy mode is option of kube-proxy. options: iptables|ipvs. default: ipvs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Service<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The CIDR block for the service network. It cannot be duplicated with the VPC CIDR and CIDR used by Kubernetes cluster in VPC, cannot be modified after creation.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Slb<wbr>Internet<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to create internet load balancer for API Server. Default to true.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>User<wbr>Ca</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of customized CA cert, you can use this CA to sign client certs to connect your cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Desired Kubernetes version. If you do not specify a value, the latest available version at resource creation is used and no upgrades will occur except you set a higher version number. The value must be configured and increased to upgrade the version when desired. Downgrades are not supported by ACK.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Auto<wbr>Renew</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Enable worker payment auto-renew, defaults to false.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Auto<wbr>Renew<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Worker payment auto-renew period. When period unit is `Month`, it can be one of {“1”, “2”, “3”, “6”, “12”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Data<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Data<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The system disk category of worker node. Its valid value are `cloud_ssd` and `cloud_efficiency`. Default to `cloud_efficiency`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The system disk size of worker node. Its valid value range [20~32768] in GB. Default to 20.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Instance<wbr>Charge<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Worker payment type. `PrePaid` or `PostPaid`, defaults to `PostPaid`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Worker<wbr>Instance<wbr>Types</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}The instance type of worker node. Specify one type for single AZ Cluster, three types for MultiAZ Cluster.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Worker<wbr>Number</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The worker node number of the kubernetes cluster. Default to 3. It is limited up to 50 and if you want to enlarge it, please apply white list or contact with us.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Worker payment period. When period unit is `Month`, it can be one of { “1”, “2”, “3”, “4”, “5”, “6”, “7”, “8”, “9”, “12”, “24”, “36”,”48”,”60”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”, “4”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Period<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Worker payment period unit. `Month` or `Week`, defaults to `Month`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Worker<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>addons</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesaddon">Managed<wbr>Kubernetes<wbr>Addon[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>availability<wbr>Zone</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Zone where new kubernetes cluster will be located. If it is not be specified, the `vswitch_ids` should be set, its value will be vswitch's zone.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>client<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of client certificate, like `~/.kube/client-cert.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>client<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of client key, like `~/.kube/client-key.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cluster<wbr>Ca<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of cluster ca certificate, like `~/.kube/cluster-ca-cert.pem`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cpu<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}kubelet cpu policy. options: static|none. default: none.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Ssh</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Enable login to the node through SSH. default: false 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Custom Image support. Must based on CentOS7 or AliyunLinux2.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>install<wbr>Cloud<wbr>Monitor</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Install cloud monitor agent on ECS. default: true 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The keypair of ssh login cluster node, you have to create it first. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kms<wbr>Encrypted<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}An KMS encrypts password used to a cs kubernetes. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kms<wbr>Encryption<wbr>Context</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}?</span>
    </dt>
    <dd>{{% md %}}An KMS encryption context used to decrypt `kms_encrypted_password` before creating or updating a cs kubernetes with `kms_encrypted_password`. See [Encryption Context](https://www.alibabacloud.com/help/doc-detail/42975.htm). It is valid when `kms_encrypted_password` is set.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kube<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of kube config, like `~/.kube/config`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name<wbr>Prefix</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>new<wbr>Nat<wbr>Gateway</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to create a new nat gateway while creating kubernetes cluster. Default to true. Then openapi in Alibaba Cloud are not all on intranet, So turn this option on is a good choice.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>node<wbr>Cidr<wbr>Mask</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The node cidr block to specific how many pods can run on single node. 24-28 is allowed. 24 means 2^(32-24)-1=255 and the node can run at most 255 pods. default: 24
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password of ssh login cluster node. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pod<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}[Flannel Specific] The CIDR block for the pod network when using Flannel. 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pod<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}[Terway Specific] The vswitches for the pod network when using Terway.Be careful the `pod_vswitch_ids` can not equal to `worker_vswtich_ids`.but must be in same availability zones.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>proxy<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Proxy mode is option of kube-proxy. options: iptables|ipvs. default: ipvs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>service<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The CIDR block for the service network. It cannot be duplicated with the VPC CIDR and CIDR used by Kubernetes cluster in VPC, cannot be modified after creation.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>slb<wbr>Internet<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to create internet load balancer for API Server. Default to true.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>user<wbr>Ca</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of customized CA cert, you can use this CA to sign client certs to connect your cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Desired Kubernetes version. If you do not specify a value, the latest available version at resource creation is used and no upgrades will occur except you set a higher version number. The value must be configured and increased to upgrade the version when desired. Downgrades are not supported by ACK.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Auto<wbr>Renew</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Enable worker payment auto-renew, defaults to false.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Auto<wbr>Renew<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Worker payment auto-renew period. When period unit is `Month`, it can be one of {“1”, “2”, “3”, “6”, “12”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Data<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Data<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The system disk category of worker node. Its valid value are `cloud_ssd` and `cloud_efficiency`. Default to `cloud_efficiency`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The system disk size of worker node. Its valid value range [20~32768] in GB. Default to 20.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Instance<wbr>Charge<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Worker payment type. `PrePaid` or `PostPaid`, defaults to `PostPaid`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>worker<wbr>Instance<wbr>Types</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}The instance type of worker node. Specify one type for single AZ Cluster, three types for MultiAZ Cluster.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>worker<wbr>Number</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}The worker node number of the kubernetes cluster. Default to 3. It is limited up to 50 and if you want to enlarge it, please apply white list or contact with us.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Worker payment period. When period unit is `Month`, it can be one of { “1”, “2”, “3”, “4”, “5”, “6”, “7”, “8”, “9”, “12”, “24”, “36”,”48”,”60”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”, “4”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Period<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Worker payment period unit. `Month` or `Week`, defaults to `Month`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>worker<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>addons</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesaddon">List[Managed<wbr>Kubernetes<wbr>Addon]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>availability_<wbr>zone</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Zone where new kubernetes cluster will be located. If it is not be specified, the `vswitch_ids` should be set, its value will be vswitch's zone.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>client_<wbr>cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of client certificate, like `~/.kube/client-cert.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>client_<wbr>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of client key, like `~/.kube/client-key.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cluster_<wbr>ca_<wbr>cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of cluster ca certificate, like `~/.kube/cluster-ca-cert.pem`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cpu_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}kubelet cpu policy. options: static|none. default: none.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable_<wbr>ssh</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable login to the node through SSH. default: false 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>image_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Custom Image support. Must based on CentOS7 or AliyunLinux2.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>install_<wbr>cloud_<wbr>monitor</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Install cloud monitor agent on ECS. default: true 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The keypair of ssh login cluster node, you have to create it first. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kms_<wbr>encrypted_<wbr>password</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}An KMS encrypts password used to a cs kubernetes. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kms_<wbr>encryption_<wbr>context</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}An KMS encryption context used to decrypt `kms_encrypted_password` before creating or updating a cs kubernetes with `kms_encrypted_password`. See [Encryption Context](https://www.alibabacloud.com/help/doc-detail/42975.htm). It is valid when `kms_encrypted_password` is set.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kube_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of kube config, like `~/.kube/config`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name_<wbr>prefix</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>new_<wbr>nat_<wbr>gateway</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to create a new nat gateway while creating kubernetes cluster. Default to true. Then openapi in Alibaba Cloud are not all on intranet, So turn this option on is a good choice.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>node_<wbr>cidr_<wbr>mask</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The node cidr block to specific how many pods can run on single node. 24-28 is allowed. 24 means 2^(32-24)-1=255 and the node can run at most 255 pods. default: 24
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>password</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The password of ssh login cluster node. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pod_<wbr>cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}[Flannel Specific] The CIDR block for the pod network when using Flannel. 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pod_<wbr>vswitch_<wbr>ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}[Terway Specific] The vswitches for the pod network when using Terway.Be careful the `pod_vswitch_ids` can not equal to `worker_vswtich_ids`.but must be in same availability zones.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>proxy_<wbr>mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Proxy mode is option of kube-proxy. options: iptables|ipvs. default: ipvs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>service_<wbr>cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The CIDR block for the service network. It cannot be duplicated with the VPC CIDR and CIDR used by Kubernetes cluster in VPC, cannot be modified after creation.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>slb_<wbr>internet_<wbr>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to create internet load balancer for API Server. Default to true.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>user_<wbr>ca</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of customized CA cert, you can use this CA to sign client certs to connect your cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Desired Kubernetes version. If you do not specify a value, the latest available version at resource creation is used and no upgrades will occur except you set a higher version number. The value must be configured and increased to upgrade the version when desired. Downgrades are not supported by ACK.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>auto_<wbr>renew</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable worker payment auto-renew, defaults to false.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>auto_<wbr>renew_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Worker payment auto-renew period. When period unit is `Month`, it can be one of {“1”, “2”, “3”, “6”, “12”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>data_<wbr>disk_<wbr>category</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>data_<wbr>disk_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>disk_<wbr>category</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The system disk category of worker node. Its valid value are `cloud_ssd` and `cloud_efficiency`. Default to `cloud_efficiency`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>disk_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The system disk size of worker node. Its valid value range [20~32768] in GB. Default to 20.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>instance_<wbr>charge_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Worker payment type. `PrePaid` or `PostPaid`, defaults to `PostPaid`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>worker_<wbr>instance_<wbr>types</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}The instance type of worker node. Specify one type for single AZ Cluster, three types for MultiAZ Cluster.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>worker_<wbr>number</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The worker node number of the kubernetes cluster. Default to 3. It is limited up to 50 and if you want to enlarge it, please apply white list or contact with us.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Worker payment period. When period unit is `Month`, it can be one of { “1”, “2”, “3”, “4”, “5”, “6”, “7”, “8”, “9”, “12”, “24”, “36”,”48”,”60”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”, “4”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>period_<wbr>unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Worker payment period unit. `Month` or `Week`, defaults to `Month`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>worker_<wbr>vswitch_<wbr>ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## ManagedKubernetes Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Addons</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesaddon">List&lt;Managed<wbr>Kubernetes<wbr>Addon&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Availability<wbr>Zone</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Zone where new kubernetes cluster will be located. If it is not be specified, the `vswitch_ids` should be set, its value will be vswitch's zone.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Client<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of client certificate, like `~/.kube/client-cert.pem`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Client<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of client key, like `~/.kube/client-key.pem`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Cluster<wbr>Ca<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of cluster ca certificate, like `~/.kube/cluster-ca-cert.pem`
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesconnections">Managed<wbr>Kubernetes<wbr>Connections</a></span>
    </dt>
    <dd>{{% md %}}Map of kubernetes cluster connection information. It contains several attributes to `Block Connections`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Cpu<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}kubelet cpu policy. options: static|none. default: none.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enable<wbr>Ssh</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Enable login to the node through SSH. default: false 
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Custom Image support. Must based on CentOS7 or AliyunLinux2.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Install<wbr>Cloud<wbr>Monitor</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Install cloud monitor agent on ECS. default: true 
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The keypair of ssh login cluster node, you have to create it first. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Kms<wbr>Encrypted<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}An KMS encrypts password used to a cs kubernetes. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Kms<wbr>Encryption<wbr>Context</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, object>?</span>
    </dt>
    <dd>{{% md %}}An KMS encryption context used to decrypt `kms_encrypted_password` before creating or updating a cs kubernetes with `kms_encrypted_password`. See [Encryption Context](https://www.alibabacloud.com/help/doc-detail/42975.htm). It is valid when `kms_encrypted_password` is set.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Kube<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of kube config, like `~/.kube/config`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name<wbr>Prefix</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Nat<wbr>Gateway<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of nat gateway used to launch kubernetes cluster.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>New<wbr>Nat<wbr>Gateway</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to create a new nat gateway while creating kubernetes cluster. Default to true. Then openapi in Alibaba Cloud are not all on intranet, So turn this option on is a good choice.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Node<wbr>Cidr<wbr>Mask</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The node cidr block to specific how many pods can run on single node. 24-28 is allowed. 24 means 2^(32-24)-1=255 and the node can run at most 255 pods. default: 24
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password of ssh login cluster node. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Pod<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}[Flannel Specific] The CIDR block for the pod network when using Flannel. 
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Pod<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}[Terway Specific] The vswitches for the pod network when using Terway.Be careful the `pod_vswitch_ids` can not equal to `worker_vswtich_ids`.but must be in same availability zones.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Proxy<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Proxy mode is option of kube-proxy. options: iptables|ipvs. default: ipvs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Security<wbr>Group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of security group where the current cluster worker node is located.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Service<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The CIDR block for the service network. It cannot be duplicated with the VPC CIDR and CIDR used by Kubernetes cluster in VPC, cannot be modified after creation.
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>Slb<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;slb_id&#39; has been deprecated from provider version 1.9.2. New field &#39;slb_internet&#39; replaces it.{{% /md %}}</p></dd>

    <dt class="property-"
            title="">
        <span>Slb<wbr>Internet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Slb<wbr>Internet<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to create internet load balancer for API Server. Default to true.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Slb<wbr>Intranet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of private load balancer where the current cluster master node is located.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>User<wbr>Ca</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of customized CA cert, you can use this CA to sign client certs to connect your cluster.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Desired Kubernetes version. If you do not specify a value, the latest available version at resource creation is used and no upgrades will occur except you set a higher version number. The value must be configured and increased to upgrade the version when desired. Downgrades are not supported by ACK.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Vpc<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of VPC where the current cluster is located.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Auto<wbr>Renew</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Enable worker payment auto-renew, defaults to false.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Auto<wbr>Renew<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Worker payment auto-renew period. When period unit is `Month`, it can be one of {“1”, “2”, “3”, “6”, “12”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”}.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Data<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Data<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The system disk category of worker node. Its valid value are `cloud_ssd` and `cloud_efficiency`. Default to `cloud_efficiency`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The system disk size of worker node. Its valid value range [20~32768] in GB. Default to 20.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Instance<wbr>Charge<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Worker payment type. `PrePaid` or `PostPaid`, defaults to `PostPaid`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Instance<wbr>Types</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}The instance type of worker node. Specify one type for single AZ Cluster, three types for MultiAZ Cluster.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Nodes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesworkernode">List&lt;Managed<wbr>Kubernetes<wbr>Worker<wbr>Node&gt;</a></span>
    </dt>
    <dd>{{% md %}}List of cluster worker nodes. It contains several attributes to `Block Nodes`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Number</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The worker node number of the kubernetes cluster. Default to 3. It is limited up to 50 and if you want to enlarge it, please apply white list or contact with us.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Worker payment period. When period unit is `Month`, it can be one of { “1”, “2”, “3”, “4”, “5”, “6”, “7”, “8”, “9”, “12”, “24”, “36”,”48”,”60”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”, “4”}.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Period<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Worker payment period unit. `Month` or `Week`, defaults to `Month`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Addons</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesaddon">[]Managed<wbr>Kubernetes<wbr>Addon</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Availability<wbr>Zone</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Zone where new kubernetes cluster will be located. If it is not be specified, the `vswitch_ids` should be set, its value will be vswitch's zone.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Client<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of client certificate, like `~/.kube/client-cert.pem`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Client<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of client key, like `~/.kube/client-key.pem`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Cluster<wbr>Ca<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of cluster ca certificate, like `~/.kube/cluster-ca-cert.pem`
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesconnections">Managed<wbr>Kubernetes<wbr>Connections</a></span>
    </dt>
    <dd>{{% md %}}Map of kubernetes cluster connection information. It contains several attributes to `Block Connections`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Cpu<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}kubelet cpu policy. options: static|none. default: none.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enable<wbr>Ssh</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Enable login to the node through SSH. default: false 
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Custom Image support. Must based on CentOS7 or AliyunLinux2.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Install<wbr>Cloud<wbr>Monitor</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Install cloud monitor agent on ECS. default: true 
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The keypair of ssh login cluster node, you have to create it first. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Kms<wbr>Encrypted<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}An KMS encrypts password used to a cs kubernetes. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Kms<wbr>Encryption<wbr>Context</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}An KMS encryption context used to decrypt `kms_encrypted_password` before creating or updating a cs kubernetes with `kms_encrypted_password`. See [Encryption Context](https://www.alibabacloud.com/help/doc-detail/42975.htm). It is valid when `kms_encrypted_password` is set.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Kube<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of kube config, like `~/.kube/config`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name<wbr>Prefix</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Nat<wbr>Gateway<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of nat gateway used to launch kubernetes cluster.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>New<wbr>Nat<wbr>Gateway</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to create a new nat gateway while creating kubernetes cluster. Default to true. Then openapi in Alibaba Cloud are not all on intranet, So turn this option on is a good choice.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Node<wbr>Cidr<wbr>Mask</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The node cidr block to specific how many pods can run on single node. 24-28 is allowed. 24 means 2^(32-24)-1=255 and the node can run at most 255 pods. default: 24
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The password of ssh login cluster node. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Pod<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}[Flannel Specific] The CIDR block for the pod network when using Flannel. 
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Pod<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}[Terway Specific] The vswitches for the pod network when using Terway.Be careful the `pod_vswitch_ids` can not equal to `worker_vswtich_ids`.but must be in same availability zones.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Proxy<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Proxy mode is option of kube-proxy. options: iptables|ipvs. default: ipvs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Security<wbr>Group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of security group where the current cluster worker node is located.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Service<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The CIDR block for the service network. It cannot be duplicated with the VPC CIDR and CIDR used by Kubernetes cluster in VPC, cannot be modified after creation.
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>Slb<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;slb_id&#39; has been deprecated from provider version 1.9.2. New field &#39;slb_internet&#39; replaces it.{{% /md %}}</p></dd>

    <dt class="property-"
            title="">
        <span>Slb<wbr>Internet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Slb<wbr>Internet<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to create internet load balancer for API Server. Default to true.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Slb<wbr>Intranet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of private load balancer where the current cluster master node is located.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>User<wbr>Ca</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of customized CA cert, you can use this CA to sign client certs to connect your cluster.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Desired Kubernetes version. If you do not specify a value, the latest available version at resource creation is used and no upgrades will occur except you set a higher version number. The value must be configured and increased to upgrade the version when desired. Downgrades are not supported by ACK.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Vpc<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of VPC where the current cluster is located.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Auto<wbr>Renew</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Enable worker payment auto-renew, defaults to false.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Auto<wbr>Renew<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Worker payment auto-renew period. When period unit is `Month`, it can be one of {“1”, “2”, “3”, “6”, “12”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”}.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Data<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Data<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The system disk category of worker node. Its valid value are `cloud_ssd` and `cloud_efficiency`. Default to `cloud_efficiency`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The system disk size of worker node. Its valid value range [20~32768] in GB. Default to 20.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Instance<wbr>Charge<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Worker payment type. `PrePaid` or `PostPaid`, defaults to `PostPaid`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Instance<wbr>Types</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}The instance type of worker node. Specify one type for single AZ Cluster, three types for MultiAZ Cluster.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Nodes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesworkernode">[]Managed<wbr>Kubernetes<wbr>Worker<wbr>Node</a></span>
    </dt>
    <dd>{{% md %}}List of cluster worker nodes. It contains several attributes to `Block Nodes`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Number</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The worker node number of the kubernetes cluster. Default to 3. It is limited up to 50 and if you want to enlarge it, please apply white list or contact with us.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Worker payment period. When period unit is `Month`, it can be one of { “1”, “2”, “3”, “4”, “5”, “6”, “7”, “8”, “9”, “12”, “24”, “36”,”48”,”60”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”, “4”}.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Period<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Worker payment period unit. `Month` or `Week`, defaults to `Month`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Worker<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>addons</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesaddon">Managed<wbr>Kubernetes<wbr>Addon[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>availability<wbr>Zone</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Zone where new kubernetes cluster will be located. If it is not be specified, the `vswitch_ids` should be set, its value will be vswitch's zone.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>client<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of client certificate, like `~/.kube/client-cert.pem`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>client<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of client key, like `~/.kube/client-key.pem`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>cluster<wbr>Ca<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of cluster ca certificate, like `~/.kube/cluster-ca-cert.pem`
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesconnections">Managed<wbr>Kubernetes<wbr>Connections</a></span>
    </dt>
    <dd>{{% md %}}Map of kubernetes cluster connection information. It contains several attributes to `Block Connections`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>cpu<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}kubelet cpu policy. options: static|none. default: none.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enable<wbr>Ssh</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Enable login to the node through SSH. default: false 
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Custom Image support. Must based on CentOS7 or AliyunLinux2.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>install<wbr>Cloud<wbr>Monitor</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Install cloud monitor agent on ECS. default: true 
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The keypair of ssh login cluster node, you have to create it first. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>kms<wbr>Encrypted<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}An KMS encrypts password used to a cs kubernetes. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>kms<wbr>Encryption<wbr>Context</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}?</span>
    </dt>
    <dd>{{% md %}}An KMS encryption context used to decrypt `kms_encrypted_password` before creating or updating a cs kubernetes with `kms_encrypted_password`. See [Encryption Context](https://www.alibabacloud.com/help/doc-detail/42975.htm). It is valid when `kms_encrypted_password` is set.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>kube<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of kube config, like `~/.kube/config`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name<wbr>Prefix</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>nat<wbr>Gateway<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of nat gateway used to launch kubernetes cluster.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>new<wbr>Nat<wbr>Gateway</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to create a new nat gateway while creating kubernetes cluster. Default to true. Then openapi in Alibaba Cloud are not all on intranet, So turn this option on is a good choice.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>node<wbr>Cidr<wbr>Mask</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The node cidr block to specific how many pods can run on single node. 24-28 is allowed. 24 means 2^(32-24)-1=255 and the node can run at most 255 pods. default: 24
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password of ssh login cluster node. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>pod<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}[Flannel Specific] The CIDR block for the pod network when using Flannel. 
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>pod<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}[Terway Specific] The vswitches for the pod network when using Terway.Be careful the `pod_vswitch_ids` can not equal to `worker_vswtich_ids`.but must be in same availability zones.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>proxy<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Proxy mode is option of kube-proxy. options: iptables|ipvs. default: ipvs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>security<wbr>Group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of security group where the current cluster worker node is located.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>service<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The CIDR block for the service network. It cannot be duplicated with the VPC CIDR and CIDR used by Kubernetes cluster in VPC, cannot be modified after creation.
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>slb<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;slb_id&#39; has been deprecated from provider version 1.9.2. New field &#39;slb_internet&#39; replaces it.{{% /md %}}</p></dd>

    <dt class="property-"
            title="">
        <span>slb<wbr>Internet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>slb<wbr>Internet<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to create internet load balancer for API Server. Default to true.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>slb<wbr>Intranet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of private load balancer where the current cluster master node is located.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>user<wbr>Ca</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of customized CA cert, you can use this CA to sign client certs to connect your cluster.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Desired Kubernetes version. If you do not specify a value, the latest available version at resource creation is used and no upgrades will occur except you set a higher version number. The value must be configured and increased to upgrade the version when desired. Downgrades are not supported by ACK.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>vpc<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of VPC where the current cluster is located.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Auto<wbr>Renew</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Enable worker payment auto-renew, defaults to false.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Auto<wbr>Renew<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Worker payment auto-renew period. When period unit is `Month`, it can be one of {“1”, “2”, “3”, “6”, “12”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”}.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Data<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Data<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The system disk category of worker node. Its valid value are `cloud_ssd` and `cloud_efficiency`. Default to `cloud_efficiency`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The system disk size of worker node. Its valid value range [20~32768] in GB. Default to 20.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Instance<wbr>Charge<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Worker payment type. `PrePaid` or `PostPaid`, defaults to `PostPaid`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Instance<wbr>Types</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}The instance type of worker node. Specify one type for single AZ Cluster, three types for MultiAZ Cluster.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Nodes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesworkernode">Managed<wbr>Kubernetes<wbr>Worker<wbr>Node[]</a></span>
    </dt>
    <dd>{{% md %}}List of cluster worker nodes. It contains several attributes to `Block Nodes`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Number</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}The worker node number of the kubernetes cluster. Default to 3. It is limited up to 50 and if you want to enlarge it, please apply white list or contact with us.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Worker payment period. When period unit is `Month`, it can be one of { “1”, “2”, “3”, “4”, “5”, “6”, “7”, “8”, “9”, “12”, “24”, “36”,”48”,”60”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”, “4”}.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Period<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Worker payment period unit. `Month` or `Week`, defaults to `Month`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>addons</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesaddon">List[Managed<wbr>Kubernetes<wbr>Addon]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>availability_<wbr>zone</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Zone where new kubernetes cluster will be located. If it is not be specified, the `vswitch_ids` should be set, its value will be vswitch's zone.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>client_<wbr>cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of client certificate, like `~/.kube/client-cert.pem`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>client_<wbr>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of client key, like `~/.kube/client-key.pem`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>cluster_<wbr>ca_<wbr>cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of cluster ca certificate, like `~/.kube/cluster-ca-cert.pem`
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesconnections">Dict[Managed<wbr>Kubernetes<wbr>Connections]</a></span>
    </dt>
    <dd>{{% md %}}Map of kubernetes cluster connection information. It contains several attributes to `Block Connections`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>cpu_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}kubelet cpu policy. options: static|none. default: none.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enable_<wbr>ssh</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable login to the node through SSH. default: false 
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>image_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Custom Image support. Must based on CentOS7 or AliyunLinux2.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>install_<wbr>cloud_<wbr>monitor</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Install cloud monitor agent on ECS. default: true 
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>key_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The keypair of ssh login cluster node, you have to create it first. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>kms_<wbr>encrypted_<wbr>password</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}An KMS encrypts password used to a cs kubernetes. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>kms_<wbr>encryption_<wbr>context</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}An KMS encryption context used to decrypt `kms_encrypted_password` before creating or updating a cs kubernetes with `kms_encrypted_password`. See [Encryption Context](https://www.alibabacloud.com/help/doc-detail/42975.htm). It is valid when `kms_encrypted_password` is set.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>kube_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of kube config, like `~/.kube/config`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name_<wbr>prefix</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>nat_<wbr>gateway_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of nat gateway used to launch kubernetes cluster.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>new_<wbr>nat_<wbr>gateway</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to create a new nat gateway while creating kubernetes cluster. Default to true. Then openapi in Alibaba Cloud are not all on intranet, So turn this option on is a good choice.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>node_<wbr>cidr_<wbr>mask</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The node cidr block to specific how many pods can run on single node. 24-28 is allowed. 24 means 2^(32-24)-1=255 and the node can run at most 255 pods. default: 24
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>password</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The password of ssh login cluster node. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>pod_<wbr>cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}[Flannel Specific] The CIDR block for the pod network when using Flannel. 
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>pod_<wbr>vswitch_<wbr>ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}[Terway Specific] The vswitches for the pod network when using Terway.Be careful the `pod_vswitch_ids` can not equal to `worker_vswtich_ids`.but must be in same availability zones.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>proxy_<wbr>mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Proxy mode is option of kube-proxy. options: iptables|ipvs. default: ipvs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>security_<wbr>group_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of security group where the current cluster worker node is located.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>service_<wbr>cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The CIDR block for the service network. It cannot be duplicated with the VPC CIDR and CIDR used by Kubernetes cluster in VPC, cannot be modified after creation.
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>slb_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;slb_id&#39; has been deprecated from provider version 1.9.2. New field &#39;slb_internet&#39; replaces it.{{% /md %}}</p></dd>

    <dt class="property-"
            title="">
        <span>slb_<wbr>internet</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>slb_<wbr>internet_<wbr>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to create internet load balancer for API Server. Default to true.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>slb_<wbr>intranet</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of private load balancer where the current cluster master node is located.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>user_<wbr>ca</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of customized CA cert, you can use this CA to sign client certs to connect your cluster.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Desired Kubernetes version. If you do not specify a value, the latest available version at resource creation is used and no upgrades will occur except you set a higher version number. The value must be configured and increased to upgrade the version when desired. Downgrades are not supported by ACK.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>vpc_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of VPC where the current cluster is located.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>auto_<wbr>renew</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable worker payment auto-renew, defaults to false.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>auto_<wbr>renew_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Worker payment auto-renew period. When period unit is `Month`, it can be one of {“1”, “2”, “3”, “6”, “12”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”}.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>data_<wbr>disk_<wbr>category</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>data_<wbr>disk_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>disk_<wbr>category</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The system disk category of worker node. Its valid value are `cloud_ssd` and `cloud_efficiency`. Default to `cloud_efficiency`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>disk_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The system disk size of worker node. Its valid value range [20~32768] in GB. Default to 20.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>instance_<wbr>charge_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Worker payment type. `PrePaid` or `PostPaid`, defaults to `PostPaid`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>instance_<wbr>types</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}The instance type of worker node. Specify one type for single AZ Cluster, three types for MultiAZ Cluster.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>nodes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesworkernode">List[Managed<wbr>Kubernetes<wbr>Worker<wbr>Node]</a></span>
    </dt>
    <dd>{{% md %}}List of cluster worker nodes. It contains several attributes to `Block Nodes`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>number</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The worker node number of the kubernetes cluster. Default to 3. It is limited up to 50 and if you want to enlarge it, please apply white list or contact with us.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Worker payment period. When period unit is `Month`, it can be one of { “1”, “2”, “3”, “4”, “5”, “6”, “7”, “8”, “9”, “12”, “24”, “36”,”48”,”60”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”, “4”}.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>period_<wbr>unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Worker payment period unit. `Month` or `Week`, defaults to `Month`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>worker_<wbr>vswitch_<wbr>ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing ManagedKubernetes Resource

Get an existing ManagedKubernetes resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">Input&lt;ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/cs/#ManagedKubernetesState">ManagedKubernetesState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/cs/#ManagedKubernetes">ManagedKubernetes</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>addons=None<span class="p">, </span>availability_zone=None<span class="p">, </span>client_cert=None<span class="p">, </span>client_key=None<span class="p">, </span>cluster_ca_cert=None<span class="p">, </span>connections=None<span class="p">, </span>cpu_policy=None<span class="p">, </span>enable_ssh=None<span class="p">, </span>image_id=None<span class="p">, </span>install_cloud_monitor=None<span class="p">, </span>key_name=None<span class="p">, </span>kms_encrypted_password=None<span class="p">, </span>kms_encryption_context=None<span class="p">, </span>kube_config=None<span class="p">, </span>name=None<span class="p">, </span>name_prefix=None<span class="p">, </span>nat_gateway_id=None<span class="p">, </span>new_nat_gateway=None<span class="p">, </span>node_cidr_mask=None<span class="p">, </span>password=None<span class="p">, </span>pod_cidr=None<span class="p">, </span>pod_vswitch_ids=None<span class="p">, </span>proxy_mode=None<span class="p">, </span>security_group_id=None<span class="p">, </span>service_cidr=None<span class="p">, </span>slb_id=None<span class="p">, </span>slb_internet=None<span class="p">, </span>slb_internet_enabled=None<span class="p">, </span>slb_intranet=None<span class="p">, </span>user_ca=None<span class="p">, </span>version=None<span class="p">, </span>vpc_id=None<span class="p">, </span>worker_auto_renew=None<span class="p">, </span>worker_auto_renew_period=None<span class="p">, </span>worker_data_disk_category=None<span class="p">, </span>worker_data_disk_size=None<span class="p">, </span>worker_disk_category=None<span class="p">, </span>worker_disk_size=None<span class="p">, </span>worker_instance_charge_type=None<span class="p">, </span>worker_instance_types=None<span class="p">, </span>worker_nodes=None<span class="p">, </span>worker_number=None<span class="p">, </span>worker_period=None<span class="p">, </span>worker_period_unit=None<span class="p">, </span>worker_vswitch_ids=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetManagedKubernetes<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/cs?tab=doc#ManagedKubernetesState">ManagedKubernetesState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/cs?tab=doc#ManagedKubernetes">ManagedKubernetes</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Cs.ManagedKubernetes.html">ManagedKubernetes</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Cs.ManagedKubernetesState.html">ManagedKubernetesState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>resource_name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Optional">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

The following state arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Addons</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesaddon">List&lt;Managed<wbr>Kubernetes<wbr>Addon<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Availability<wbr>Zone</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Zone where new kubernetes cluster will be located. If it is not be specified, the `vswitch_ids` should be set, its value will be vswitch's zone.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Client<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of client certificate, like `~/.kube/client-cert.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Client<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of client key, like `~/.kube/client-key.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cluster<wbr>Ca<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of cluster ca certificate, like `~/.kube/cluster-ca-cert.pem`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesconnections">Managed<wbr>Kubernetes<wbr>Connections<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}Map of kubernetes cluster connection information. It contains several attributes to `Block Connections`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}kubelet cpu policy. options: static|none. default: none.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Ssh</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Enable login to the node through SSH. default: false 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Custom Image support. Must based on CentOS7 or AliyunLinux2.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Install<wbr>Cloud<wbr>Monitor</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Install cloud monitor agent on ECS. default: true 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The keypair of ssh login cluster node, you have to create it first. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kms<wbr>Encrypted<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}An KMS encrypts password used to a cs kubernetes. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kms<wbr>Encryption<wbr>Context</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, object>?</span>
    </dt>
    <dd>{{% md %}}An KMS encryption context used to decrypt `kms_encrypted_password` before creating or updating a cs kubernetes with `kms_encrypted_password`. See [Encryption Context](https://www.alibabacloud.com/help/doc-detail/42975.htm). It is valid when `kms_encrypted_password` is set.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kube<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of kube config, like `~/.kube/config`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name<wbr>Prefix</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Nat<wbr>Gateway<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of nat gateway used to launch kubernetes cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>New<wbr>Nat<wbr>Gateway</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to create a new nat gateway while creating kubernetes cluster. Default to true. Then openapi in Alibaba Cloud are not all on intranet, So turn this option on is a good choice.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Node<wbr>Cidr<wbr>Mask</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The node cidr block to specific how many pods can run on single node. 24-28 is allowed. 24 means 2^(32-24)-1=255 and the node can run at most 255 pods. default: 24
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password of ssh login cluster node. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pod<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}[Flannel Specific] The CIDR block for the pod network when using Flannel. 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pod<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}[Terway Specific] The vswitches for the pod network when using Terway.Be careful the `pod_vswitch_ids` can not equal to `worker_vswtich_ids`.but must be in same availability zones.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Proxy<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Proxy mode is option of kube-proxy. options: iptables|ipvs. default: ipvs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Security<wbr>Group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of security group where the current cluster worker node is located.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Service<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The CIDR block for the service network. It cannot be duplicated with the VPC CIDR and CIDR used by Kubernetes cluster in VPC, cannot be modified after creation.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Slb<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;slb_id&#39; has been deprecated from provider version 1.9.2. New field &#39;slb_internet&#39; replaces it.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Slb<wbr>Internet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Slb<wbr>Internet<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Whether to create internet load balancer for API Server. Default to true.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Slb<wbr>Intranet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of private load balancer where the current cluster master node is located.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>User<wbr>Ca</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of customized CA cert, you can use this CA to sign client certs to connect your cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Desired Kubernetes version. If you do not specify a value, the latest available version at resource creation is used and no upgrades will occur except you set a higher version number. The value must be configured and increased to upgrade the version when desired. Downgrades are not supported by ACK.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Vpc<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of VPC where the current cluster is located.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Auto<wbr>Renew</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Enable worker payment auto-renew, defaults to false.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Auto<wbr>Renew<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Worker payment auto-renew period. When period unit is `Month`, it can be one of {“1”, “2”, “3”, “6”, “12”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Data<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Data<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The system disk category of worker node. Its valid value are `cloud_ssd` and `cloud_efficiency`. Default to `cloud_efficiency`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The system disk size of worker node. Its valid value range [20~32768] in GB. Default to 20.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Instance<wbr>Charge<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Worker payment type. `PrePaid` or `PostPaid`, defaults to `PostPaid`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Instance<wbr>Types</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}The instance type of worker node. Specify one type for single AZ Cluster, three types for MultiAZ Cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Nodes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesworkernode">List&lt;Managed<wbr>Kubernetes<wbr>Worker<wbr>Node<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}List of cluster worker nodes. It contains several attributes to `Block Nodes`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Number</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The worker node number of the kubernetes cluster. Default to 3. It is limited up to 50 and if you want to enlarge it, please apply white list or contact with us.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Worker payment period. When period unit is `Month`, it can be one of { “1”, “2”, “3”, “4”, “5”, “6”, “7”, “8”, “9”, “12”, “24”, “36”,”48”,”60”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”, “4”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Period<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Worker payment period unit. `Month` or `Week`, defaults to `Month`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Addons</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesaddon">[]Managed<wbr>Kubernetes<wbr>Addon</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Availability<wbr>Zone</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Zone where new kubernetes cluster will be located. If it is not be specified, the `vswitch_ids` should be set, its value will be vswitch's zone.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Client<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of client certificate, like `~/.kube/client-cert.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Client<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of client key, like `~/.kube/client-key.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cluster<wbr>Ca<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of cluster ca certificate, like `~/.kube/cluster-ca-cert.pem`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesconnections">*Managed<wbr>Kubernetes<wbr>Connections</a></span>
    </dt>
    <dd>{{% md %}}Map of kubernetes cluster connection information. It contains several attributes to `Block Connections`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}kubelet cpu policy. options: static|none. default: none.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Ssh</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Enable login to the node through SSH. default: false 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Custom Image support. Must based on CentOS7 or AliyunLinux2.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Install<wbr>Cloud<wbr>Monitor</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Install cloud monitor agent on ECS. default: true 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The keypair of ssh login cluster node, you have to create it first. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kms<wbr>Encrypted<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}An KMS encrypts password used to a cs kubernetes. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kms<wbr>Encryption<wbr>Context</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}An KMS encryption context used to decrypt `kms_encrypted_password` before creating or updating a cs kubernetes with `kms_encrypted_password`. See [Encryption Context](https://www.alibabacloud.com/help/doc-detail/42975.htm). It is valid when `kms_encrypted_password` is set.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kube<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of kube config, like `~/.kube/config`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name<wbr>Prefix</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Nat<wbr>Gateway<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of nat gateway used to launch kubernetes cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>New<wbr>Nat<wbr>Gateway</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to create a new nat gateway while creating kubernetes cluster. Default to true. Then openapi in Alibaba Cloud are not all on intranet, So turn this option on is a good choice.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Node<wbr>Cidr<wbr>Mask</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The node cidr block to specific how many pods can run on single node. 24-28 is allowed. 24 means 2^(32-24)-1=255 and the node can run at most 255 pods. default: 24
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The password of ssh login cluster node. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pod<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}[Flannel Specific] The CIDR block for the pod network when using Flannel. 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pod<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}[Terway Specific] The vswitches for the pod network when using Terway.Be careful the `pod_vswitch_ids` can not equal to `worker_vswtich_ids`.but must be in same availability zones.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Proxy<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Proxy mode is option of kube-proxy. options: iptables|ipvs. default: ipvs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Security<wbr>Group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of security group where the current cluster worker node is located.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Service<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The CIDR block for the service network. It cannot be duplicated with the VPC CIDR and CIDR used by Kubernetes cluster in VPC, cannot be modified after creation.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Slb<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;slb_id&#39; has been deprecated from provider version 1.9.2. New field &#39;slb_internet&#39; replaces it.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Slb<wbr>Internet</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Slb<wbr>Internet<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Whether to create internet load balancer for API Server. Default to true.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Slb<wbr>Intranet</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of private load balancer where the current cluster master node is located.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>User<wbr>Ca</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The path of customized CA cert, you can use this CA to sign client certs to connect your cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Desired Kubernetes version. If you do not specify a value, the latest available version at resource creation is used and no upgrades will occur except you set a higher version number. The value must be configured and increased to upgrade the version when desired. Downgrades are not supported by ACK.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Vpc<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of VPC where the current cluster is located.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Auto<wbr>Renew</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Enable worker payment auto-renew, defaults to false.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Auto<wbr>Renew<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Worker payment auto-renew period. When period unit is `Month`, it can be one of {“1”, “2”, “3”, “6”, “12”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Data<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Data<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The system disk category of worker node. Its valid value are `cloud_ssd` and `cloud_efficiency`. Default to `cloud_efficiency`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The system disk size of worker node. Its valid value range [20~32768] in GB. Default to 20.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Instance<wbr>Charge<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Worker payment type. `PrePaid` or `PostPaid`, defaults to `PostPaid`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Instance<wbr>Types</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}The instance type of worker node. Specify one type for single AZ Cluster, three types for MultiAZ Cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Nodes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesworkernode">[]Managed<wbr>Kubernetes<wbr>Worker<wbr>Node</a></span>
    </dt>
    <dd>{{% md %}}List of cluster worker nodes. It contains several attributes to `Block Nodes`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Number</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The worker node number of the kubernetes cluster. Default to 3. It is limited up to 50 and if you want to enlarge it, please apply white list or contact with us.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Worker payment period. When period unit is `Month`, it can be one of { “1”, “2”, “3”, “4”, “5”, “6”, “7”, “8”, “9”, “12”, “24”, “36”,”48”,”60”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”, “4”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Period<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Worker payment period unit. `Month` or `Week`, defaults to `Month`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Worker<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>addons</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesaddon">Managed<wbr>Kubernetes<wbr>Addon[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>availability<wbr>Zone</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Zone where new kubernetes cluster will be located. If it is not be specified, the `vswitch_ids` should be set, its value will be vswitch's zone.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>client<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of client certificate, like `~/.kube/client-cert.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>client<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of client key, like `~/.kube/client-key.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cluster<wbr>Ca<wbr>Cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of cluster ca certificate, like `~/.kube/cluster-ca-cert.pem`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesconnections">Managed<wbr>Kubernetes<wbr>Connections?</a></span>
    </dt>
    <dd>{{% md %}}Map of kubernetes cluster connection information. It contains several attributes to `Block Connections`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cpu<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}kubelet cpu policy. options: static|none. default: none.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Ssh</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Enable login to the node through SSH. default: false 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Custom Image support. Must based on CentOS7 or AliyunLinux2.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>install<wbr>Cloud<wbr>Monitor</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Install cloud monitor agent on ECS. default: true 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The keypair of ssh login cluster node, you have to create it first. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kms<wbr>Encrypted<wbr>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}An KMS encrypts password used to a cs kubernetes. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kms<wbr>Encryption<wbr>Context</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}?</span>
    </dt>
    <dd>{{% md %}}An KMS encryption context used to decrypt `kms_encrypted_password` before creating or updating a cs kubernetes with `kms_encrypted_password`. See [Encryption Context](https://www.alibabacloud.com/help/doc-detail/42975.htm). It is valid when `kms_encrypted_password` is set.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kube<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of kube config, like `~/.kube/config`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name<wbr>Prefix</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>nat<wbr>Gateway<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of nat gateway used to launch kubernetes cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>new<wbr>Nat<wbr>Gateway</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to create a new nat gateway while creating kubernetes cluster. Default to true. Then openapi in Alibaba Cloud are not all on intranet, So turn this option on is a good choice.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>node<wbr>Cidr<wbr>Mask</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The node cidr block to specific how many pods can run on single node. 24-28 is allowed. 24 means 2^(32-24)-1=255 and the node can run at most 255 pods. default: 24
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The password of ssh login cluster node. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pod<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}[Flannel Specific] The CIDR block for the pod network when using Flannel. 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pod<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}[Terway Specific] The vswitches for the pod network when using Terway.Be careful the `pod_vswitch_ids` can not equal to `worker_vswtich_ids`.but must be in same availability zones.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>proxy<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Proxy mode is option of kube-proxy. options: iptables|ipvs. default: ipvs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>security<wbr>Group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of security group where the current cluster worker node is located.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>service<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The CIDR block for the service network. It cannot be duplicated with the VPC CIDR and CIDR used by Kubernetes cluster in VPC, cannot be modified after creation.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>slb<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;slb_id&#39; has been deprecated from provider version 1.9.2. New field &#39;slb_internet&#39; replaces it.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>slb<wbr>Internet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>slb<wbr>Internet<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Whether to create internet load balancer for API Server. Default to true.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>slb<wbr>Intranet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of private load balancer where the current cluster master node is located.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>user<wbr>Ca</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The path of customized CA cert, you can use this CA to sign client certs to connect your cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Desired Kubernetes version. If you do not specify a value, the latest available version at resource creation is used and no upgrades will occur except you set a higher version number. The value must be configured and increased to upgrade the version when desired. Downgrades are not supported by ACK.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>vpc<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of VPC where the current cluster is located.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Auto<wbr>Renew</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Enable worker payment auto-renew, defaults to false.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Auto<wbr>Renew<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Worker payment auto-renew period. When period unit is `Month`, it can be one of {“1”, “2”, “3”, “6”, “12”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Data<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Data<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Disk<wbr>Category</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The system disk category of worker node. Its valid value are `cloud_ssd` and `cloud_efficiency`. Default to `cloud_efficiency`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Disk<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The system disk size of worker node. Its valid value range [20~32768] in GB. Default to 20.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Instance<wbr>Charge<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Worker payment type. `PrePaid` or `PostPaid`, defaults to `PostPaid`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Instance<wbr>Types</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}The instance type of worker node. Specify one type for single AZ Cluster, three types for MultiAZ Cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Nodes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesworkernode">Managed<wbr>Kubernetes<wbr>Worker<wbr>Node[]?</a></span>
    </dt>
    <dd>{{% md %}}List of cluster worker nodes. It contains several attributes to `Block Nodes`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Number</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The worker node number of the kubernetes cluster. Default to 3. It is limited up to 50 and if you want to enlarge it, please apply white list or contact with us.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Worker payment period. When period unit is `Month`, it can be one of { “1”, “2”, “3”, “4”, “5”, “6”, “7”, “8”, “9”, “12”, “24”, “36”,”48”,”60”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”, “4”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Period<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Worker payment period unit. `Month` or `Week`, defaults to `Month`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker<wbr>Vswitch<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>addons</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesaddon">List[Managed<wbr>Kubernetes<wbr>Addon]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>availability_<wbr>zone</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Zone where new kubernetes cluster will be located. If it is not be specified, the `vswitch_ids` should be set, its value will be vswitch's zone.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>client_<wbr>cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of client certificate, like `~/.kube/client-cert.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>client_<wbr>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of client key, like `~/.kube/client-key.pem`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cluster_<wbr>ca_<wbr>cert</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of cluster ca certificate, like `~/.kube/cluster-ca-cert.pem`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesconnections">Dict[Managed<wbr>Kubernetes<wbr>Connections]</a></span>
    </dt>
    <dd>{{% md %}}Map of kubernetes cluster connection information. It contains several attributes to `Block Connections`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cpu_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}kubelet cpu policy. options: static|none. default: none.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable_<wbr>ssh</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable login to the node through SSH. default: false 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>image_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Custom Image support. Must based on CentOS7 or AliyunLinux2.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>install_<wbr>cloud_<wbr>monitor</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Install cloud monitor agent on ECS. default: true 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The keypair of ssh login cluster node, you have to create it first. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kms_<wbr>encrypted_<wbr>password</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}An KMS encrypts password used to a cs kubernetes. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kms_<wbr>encryption_<wbr>context</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}An KMS encryption context used to decrypt `kms_encrypted_password` before creating or updating a cs kubernetes with `kms_encrypted_password`. See [Encryption Context](https://www.alibabacloud.com/help/doc-detail/42975.htm). It is valid when `kms_encrypted_password` is set.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kube_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of kube config, like `~/.kube/config`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name_<wbr>prefix</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>nat_<wbr>gateway_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of nat gateway used to launch kubernetes cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>new_<wbr>nat_<wbr>gateway</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to create a new nat gateway while creating kubernetes cluster. Default to true. Then openapi in Alibaba Cloud are not all on intranet, So turn this option on is a good choice.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>node_<wbr>cidr_<wbr>mask</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The node cidr block to specific how many pods can run on single node. 24-28 is allowed. 24 means 2^(32-24)-1=255 and the node can run at most 255 pods. default: 24
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>password</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The password of ssh login cluster node. You have to specify one of `password` `key_name` `kms_encrypted_password` fields.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pod_<wbr>cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}[Flannel Specific] The CIDR block for the pod network when using Flannel. 
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pod_<wbr>vswitch_<wbr>ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}[Terway Specific] The vswitches for the pod network when using Terway.Be careful the `pod_vswitch_ids` can not equal to `worker_vswtich_ids`.but must be in same availability zones.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>proxy_<wbr>mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Proxy mode is option of kube-proxy. options: iptables|ipvs. default: ipvs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>security_<wbr>group_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of security group where the current cluster worker node is located.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>service_<wbr>cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The CIDR block for the service network. It cannot be duplicated with the VPC CIDR and CIDR used by Kubernetes cluster in VPC, cannot be modified after creation.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>slb_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Field &#39;slb_id&#39; has been deprecated from provider version 1.9.2. New field &#39;slb_internet&#39; replaces it.{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>slb_<wbr>internet</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>slb_<wbr>internet_<wbr>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Whether to create internet load balancer for API Server. Default to true.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>slb_<wbr>intranet</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of private load balancer where the current cluster master node is located.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>user_<wbr>ca</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of customized CA cert, you can use this CA to sign client certs to connect your cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Desired Kubernetes version. If you do not specify a value, the latest available version at resource creation is used and no upgrades will occur except you set a higher version number. The value must be configured and increased to upgrade the version when desired. Downgrades are not supported by ACK.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>vpc_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of VPC where the current cluster is located.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>auto_<wbr>renew</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable worker payment auto-renew, defaults to false.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>auto_<wbr>renew_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Worker payment auto-renew period. When period unit is `Month`, it can be one of {“1”, “2”, “3”, “6”, “12”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>data_<wbr>disk_<wbr>category</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>data_<wbr>disk_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>disk_<wbr>category</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The system disk category of worker node. Its valid value are `cloud_ssd` and `cloud_efficiency`. Default to `cloud_efficiency`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>disk_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The system disk size of worker node. Its valid value range [20~32768] in GB. Default to 20.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>instance_<wbr>charge_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Worker payment type. `PrePaid` or `PostPaid`, defaults to `PostPaid`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>instance_<wbr>types</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}The instance type of worker node. Specify one type for single AZ Cluster, three types for MultiAZ Cluster.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>nodes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#managedkubernetesworkernode">List[Managed<wbr>Kubernetes<wbr>Worker<wbr>Node]</a></span>
    </dt>
    <dd>{{% md %}}List of cluster worker nodes. It contains several attributes to `Block Nodes`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>number</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The worker node number of the kubernetes cluster. Default to 3. It is limited up to 50 and if you want to enlarge it, please apply white list or contact with us.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Worker payment period. When period unit is `Month`, it can be one of { “1”, “2”, “3”, “4”, “5”, “6”, “7”, “8”, “9”, “12”, “24”, “36”,”48”,”60”}.  When period unit is `Week`, it can be one of {“1”, “2”, “3”, “4”}.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>period_<wbr>unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Worker payment period unit. `Month` or `Week`, defaults to `Month`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>worker_<wbr>vswitch_<wbr>ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Supporting Types

<h4>Managed<wbr>Kubernetes<wbr>Addon</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/input/#ManagedKubernetesAddon">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/output/#ManagedKubernetesAddon">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/cs?tab=doc#ManagedKubernetesAddonArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/cs?tab=doc#ManagedKubernetesAddonOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Disabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Disabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>config</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>disabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>config</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>disabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Managed<wbr>Kubernetes<wbr>Connections</h4>
{{% choosable language nodejs %}}
> See the   <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/output/#ManagedKubernetesConnections">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the   <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/cs?tab=doc#ManagedKubernetesConnectionsOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Api<wbr>Server<wbr>Internet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}API Server Internet endpoint.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Api<wbr>Server<wbr>Intranet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}API Server Intranet endpoint.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Master<wbr>Public<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Service<wbr>Domain</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Service Access Domain.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Api<wbr>Server<wbr>Internet</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}API Server Internet endpoint.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Api<wbr>Server<wbr>Intranet</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}API Server Intranet endpoint.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Master<wbr>Public<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Service<wbr>Domain</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Service Access Domain.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>api<wbr>Server<wbr>Internet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}API Server Internet endpoint.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>api<wbr>Server<wbr>Intranet</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}API Server Intranet endpoint.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>master<wbr>Public<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>service<wbr>Domain</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Service Access Domain.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>api_<wbr>server_<wbr>internet</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}API Server Internet endpoint.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>api_<wbr>server_<wbr>intranet</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}API Server Intranet endpoint.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>master_<wbr>public_<wbr>ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>service_<wbr>domain</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Service Access Domain.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Managed<wbr>Kubernetes<wbr>Worker<wbr>Node</h4>
{{% choosable language nodejs %}}
> See the   <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/output/#ManagedKubernetesWorkerNode">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the   <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/cs?tab=doc#ManagedKubernetesWorkerNodeOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}ID of the node.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Private<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The private IP address of node.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}ID of the node.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Private<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The private IP address of node.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}ID of the node.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>private<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The private IP address of node.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}ID of the node.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The kubernetes cluster's name. It is unique in one Alicloud account.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>private_<wbr>ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The private IP address of node.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}









<h3>Package Details</h3>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-alicloud">https://github.com/pulumi/pulumi-alicloud</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
    
</dl>
