# Using the Liferay UI Taglib [](id=using-the-liferay-ui-taglib-in-your-portlets)

The Liferay UI tag library provides tags that implement commonly used UI 
components. These tags make your markup consistent, responsive, and accessible. 

You can find a list of the available `<liferay-ui>` taglibs in the 
[Liferay UI taglibdocs](https://docs.liferay.com/portal/7.1-latest/taglibs/util-taglib/liferay-ui/tld-summary.html). 
Each taglib has a list of attributes that can be passed to the tag. Some of 
these are required and some are optional. See the taglibdocs to view the 
requirements for each tag. You'll find the full markup generated by the tags in 
their JSPs in their 
[Liferay Github Repo](https://github.com/liferay/liferay-portal/tree/7.1.x/portal-web/docroot/html/taglib/ui) 
folders.

To use the Liferay-UI taglib library you must add the following declaration to 
your JSP:

    <%@ taglib prefix="liferay-ui" uri="http://liferay.com/tld/ui" %>

This section of tutorials covers how to create UI components with the Liferay UI 
taglibs. Each tutorial contains code examples along with a screenshot of the 
resulting UI. 
