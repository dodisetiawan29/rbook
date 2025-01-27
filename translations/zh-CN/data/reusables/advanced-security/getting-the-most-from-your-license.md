当您决定哪些仓库和组织优先用于 {% data variables.product.prodname_GH_advanced_security %} 时，应该查看它们并识别：

- 对公司成功至关重要的代码库。 These are the projects for which the introduction of vulnerable code, hard-coded secrets, or insecure dependencies would have the greatest impact on your company.
- 提交频率最高的代码库。 这些是最积极开发的项目，因此出现安全问题的风险较高。

对这些组织或仓库启用 {% data variables.product.prodname_GH_advanced_security %} 后，评估您可以添加哪些其他代码库，而不会对唯一提交者产生计费。 最后，查看其余重要和繁忙的代码库。 {% ifversion fpt or ghes or ghec %}如果您想增加许可证中的席位数，请联系 {% data variables.contact.contact_enterprise_sales %}。{% endif %}
