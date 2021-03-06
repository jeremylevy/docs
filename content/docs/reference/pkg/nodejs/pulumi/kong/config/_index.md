---
title: "Module config"
title_tag: "Module config | Package @pulumi/kong | Node.js SDK"
linktitle: "config"
meta_desc: "Explore members of the config module in the @pulumi/kong package."
git_sha: "020c485cceb88bbcafbcc9c1f563f22d762bb467"
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->


> This provider is a derived work of the [Terraform Provider](https://github.com/kevholditch/terraform-provider-Kong)
> distributed under [MIT](https://mit-license.org/). If you encounter a bug or missing feature,
> first check the [`pulumi/pulumi-kong` repo](https://github.com/pulumi/pulumi-kong/issues); however, if that doesn't turn up anything,
> please consult the source [`kevholditch/terraform-provider-Kong` repo](https://github.com/kevholditch/terraform-provider-Kong/issues).







<h3>APIs</h3>
<ul class="api">
    <li><a href="#kongAdminPassword"><span class="symbol api"></span>kongAdminPassword</a></li>
    <li><a href="#kongAdminToken"><span class="symbol api"></span>kongAdminToken</a></li>
    <li><a href="#kongAdminUri"><span class="symbol api"></span>kongAdminUri</a></li>
    <li><a href="#kongAdminUsername"><span class="symbol api"></span>kongAdminUsername</a></li>
    <li><a href="#kongApiKey"><span class="symbol api"></span>kongApiKey</a></li>
    <li><a href="#strictPluginsMatch"><span class="symbol api"></span>strictPluginsMatch</a></li>
    <li><a href="#tlsSkipVerify"><span class="symbol api"></span>tlsSkipVerify</a></li>
</ul>




<h2 id="apis">APIs</h2>
<h3 class="pdoc-module-header" id="kongAdminPassword" data-link-title="kongAdminPassword">
    <a href="https://github.com/pulumi/pulumi-kong/blob/020c485cceb88bbcafbcc9c1f563f22d762bb467/sdk/nodejs/config/vars.ts#L12">
        let <strong>kongAdminPassword</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> kongAdminPassword: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;kongAdminPassword&#34;) || utilities.getEnv(&#34;KONG_ADMIN_PASSWORD&#34;)</span>;</code></pre>

An basic auth password for kong admin

<h3 class="pdoc-module-header" id="kongAdminToken" data-link-title="kongAdminToken">
    <a href="https://github.com/pulumi/pulumi-kong/blob/020c485cceb88bbcafbcc9c1f563f22d762bb467/sdk/nodejs/config/vars.ts#L16">
        let <strong>kongAdminToken</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> kongAdminToken: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;kongAdminToken&#34;) || utilities.getEnv(&#34;KONG_ADMIN_TOKEN&#34;)</span>;</code></pre>

API key for the kong api (Enterprise Edition)

<h3 class="pdoc-module-header" id="kongAdminUri" data-link-title="kongAdminUri">
    <a href="https://github.com/pulumi/pulumi-kong/blob/020c485cceb88bbcafbcc9c1f563f22d762bb467/sdk/nodejs/config/vars.ts#L20">
        let <strong>kongAdminUri</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> kongAdminUri: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;kongAdminUri&#34;) || (utilities.getEnv(&#34;KONG_ADMIN_ADDR&#34;) || &#34;http://localhost:8001&#34;)</span>;</code></pre>

The address of the kong admin url e.g. http://localhost:8001

<h3 class="pdoc-module-header" id="kongAdminUsername" data-link-title="kongAdminUsername">
    <a href="https://github.com/pulumi/pulumi-kong/blob/020c485cceb88bbcafbcc9c1f563f22d762bb467/sdk/nodejs/config/vars.ts#L24">
        let <strong>kongAdminUsername</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> kongAdminUsername: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;kongAdminUsername&#34;) || utilities.getEnv(&#34;KONG_ADMIN_USERNAME&#34;)</span>;</code></pre>

An basic auth user for kong admin

<h3 class="pdoc-module-header" id="kongApiKey" data-link-title="kongApiKey">
    <a href="https://github.com/pulumi/pulumi-kong/blob/020c485cceb88bbcafbcc9c1f563f22d762bb467/sdk/nodejs/config/vars.ts#L28">
        let <strong>kongApiKey</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> kongApiKey: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;kongApiKey&#34;) || utilities.getEnv(&#34;KONG_API_KEY&#34;)</span>;</code></pre>

API key for the kong api (if you have locked it down)

<h3 class="pdoc-module-header" id="strictPluginsMatch" data-link-title="strictPluginsMatch">
    <a href="https://github.com/pulumi/pulumi-kong/blob/020c485cceb88bbcafbcc9c1f563f22d762bb467/sdk/nodejs/config/vars.ts#L32">
        let <strong>strictPluginsMatch</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> strictPluginsMatch: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;boolean&gt;(&#34;strictPluginsMatch&#34;) || utilities.getEnvBoolean(&#34;STRICT_PLUGINS_MATCH&#34;)</span>;</code></pre>

Should plugins `config_json` field strictly match plugin configuration

<h3 class="pdoc-module-header" id="tlsSkipVerify" data-link-title="tlsSkipVerify">
    <a href="https://github.com/pulumi/pulumi-kong/blob/020c485cceb88bbcafbcc9c1f563f22d762bb467/sdk/nodejs/config/vars.ts#L36">
        let <strong>tlsSkipVerify</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> tlsSkipVerify: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;boolean&gt;(&#34;tlsSkipVerify&#34;) || (utilities.getEnvBoolean(&#34;TLS_SKIP_VERIFY&#34;) || false)</span>;</code></pre>

Whether to skip tls verify for https kong api endpoint using self signed or untrusted certs

