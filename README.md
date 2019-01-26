<!-- All In One SEOYANDIRA Start -->
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<title><data:blog.pageTitle/></title>
<b:else/>
<title><data:blog.pageName/> - <data:blog.title/></title>
</b:if>
<b:if cond='data:blog.metaDescription != &quot;&quot;'>
<meta expr:content='data:blog.metaDescription' name='description'/>
</b:if>
<b:if cond='data:blog.pageType == &quot;archive&quot;'>
<meta content='noindex, nofollow' name='robots'/>
<b:else/>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<b:if cond='data:blog.url == data:blog.homepageUrl'>
<meta expr:content='data:blog.title' name='keywords'/>
<meta content='index, follow' name='robots'/>
</b:if>
<b:else/>
<b:if cond='data:blog.pageTitle != data:blog.title'>
<meta expr:content='data:blog.pageName' name='keywords'/>
</b:if>
</b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<meta content='article' property='og:type'/>
<meta expr:content='data:blog.title' property='og:site_name'/>
<meta expr:content='data:blog.pageName' property='og:title'/></b:if>
<b:if cond='data:blog.postImageThumbnailUrl'>
<meta expr:content='data:blog.postImageThumbnailUrl' property='og:image'/>
</b:if>
<meta content='global' name='distribution'/>
<meta content='1 days' name='revisit'/>
<meta content='1 days' name='revisit-after'/>
<meta content='document' name='resource-type'/>
<meta content='all' name='audience'/>
<meta content='general' name='rating'/>
<meta content='all' name='robots'/>
<meta content='en-us' name='language'/>
<meta content='USA' name='country'/>
<meta content='@twitter.com/BBeginnerCom' name='twitter:site'/>
<meta content='@BBeginnerCom' name='twitter:creator'/>
<meta content='BBeginner' name='author'/>
<meta content='contact@bbeginner.com' name='email'/>
</b:if>
<!-- All In One SEOYANDIRA End -->
