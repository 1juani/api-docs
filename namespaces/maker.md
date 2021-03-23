# (/maker)
## Scopes 
Here you can find all the scopes available in this particular namespace. 
{% api-method method="WEBSOCKET" host="" path="/maker" %}
{% api-method-summary %} cdp {% endapi-method-summary %}
{% api-method-spec %}
{% api-method-request %}
{% api-method-query-parameters %}
{% api-method-parameter name="cdp_id" type="str" %}
Default: -
{% endapi-method-parameter %}
{% api-method-parameter name="currency" type="[PriceCurrency](#pricecurrency)" %}
Default: usd
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}
{% api-method-response %}
[MakerCDP](#makercdp){% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="WEBSOCKET" host="" path="/maker" %}
{% api-method-summary %} vault {% endapi-method-summary %}
{% api-method-spec %}
{% api-method-request %}
{% api-method-query-parameters %}
{% api-method-parameter name="vault_id" type="str" %}
Default: -
{% endapi-method-parameter %}
{% api-method-parameter name="currency" type="[PriceCurrency](#pricecurrency)" %}
Default: usd
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}
{% api-method-response %}
[MakerVault](#makervault){% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="WEBSOCKET" host="" path="/maker" %}
{% api-method-summary %} cdp-actions {% endapi-method-summary %}
{% api-method-spec %}
{% api-method-request %}
{% api-method-query-parameters %}
{% api-method-parameter name="cdp_id" type="str" %}
Default: -
{% endapi-method-parameter %}
{% api-method-parameter name="currency" type="[PriceCurrency](#pricecurrency)" %}
Default: usd
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}
{% api-method-response %}
List[[MakerCDPAction](#makercdpaction)]{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="WEBSOCKET" host="" path="/maker" %}
{% api-method-summary %} vault-actions {% endapi-method-summary %}
{% api-method-spec %}
{% api-method-request %}
{% api-method-query-parameters %}
{% api-method-parameter name="vault_id" type="str" %}
Default: -
{% endapi-method-parameter %}
{% api-method-parameter name="currency" type="[PriceCurrency](#pricecurrency)" %}
Default: usd
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}
{% api-method-response %}
List[[MakerVaultAction](#makervaultaction)]{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}
