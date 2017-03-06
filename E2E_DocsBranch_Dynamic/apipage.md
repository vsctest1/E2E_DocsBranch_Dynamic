<!DOCTYPE html>
　
　
　
<html xmlns="http://www.w3.org/1999/xhtml" lang="en">
<head><meta name="ROBOTS" content="INDEX, FOLLOW" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="author" content="JimacoMS" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="ms.TocTitle" content="Operations on the signed-in user" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="search.ms_sitename" content="MSDN" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="search.ms_docsetname" content="CE_aad-graph-api-docs-pr_CE" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="version" content="0" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="ms.contentlang" content="en-us" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="ms.sitename" content="MSDN" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="search.ms_product" content="AzureGraph" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="ms.depotname" content="AzureGraph.CE_aad-graph-api-docs-pr_CE" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="ms.publishtime" content="2016-08-26 07:31 PM" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="ms.gitcommit" content="https://github.com/Microsoft/aad-graph-api-docs-pr/blob/c7884bc0f5c010c38288d9cca53c38a6ae0acbe7/docs/api/signed-in-user-operations.md" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="ms.giturl" content="https://github.com/Microsoft/aad-graph-api-docs-pr/blob/master/docs/api/signed-in-user-operations.md" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="ms.documentid" content="3c9d5104-cda2-9ac5-616c-68aba38d5108" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="ms.opspagetype" content="Conceptual" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="canonical_url" content="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/api/signed-in-user-operations" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="content_type" content="text/html" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="content_uri" content="https://opdhsblobprod02.blob.core.windows.net/contents/a72ffb9545ff48ed9649a0d004ee9729/690a3fc1cf7f426fb0f5ce4e2c247a01" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="content_secondary_uri" content="https://opdhsblobprod02-secondary.blob.core.windows.net/contents/a72ffb9545ff48ed9649a0d004ee9729/690a3fc1cf7f426fb0f5ce4e2c247a01" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta>
<meta name="ms.contentsource" content="OP" xmlns:c="urn:msdn-com:mtps/2004/1/common" xmlns="http://www.w3.org/1999/xhtml"></meta><link rel="canonical" href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/api/signed-in-user-operations" />
    <title>Azure AD Graph API Operations on the Signed-in User</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
　
　
　
<meta name="AmbientContext" content="{&quot;insight.perf_timing&quot;:true,&quot;display.use_large_font&quot;:true,&quot;layout.limit_max_width&quot;:false,&quot;AmbientContextId&quot;:&quot;AE5106CD-A295-4171-ADD1-81FF235AFEB8&quot;,&quot;insight.use_wedcs_vnext&quot;:true,&quot;display.high_contrast&quot;:true,&quot;AmbientContextDownstream&quot;:{&quot;LogTrace&quot;:false}}" />
　
<meta name="MN" content="334A90EE-7:07:17 PM" />
　
<meta name="ms.locale" content="en-us" />
　
<meta name="ms.lang" content="EN" />
　
<meta name="ms.loc" content="US" />
　
<meta name="ms.assetid" content="" />
　
<meta name="ms.auth" content="0" />
　
<meta name="ms.topic" content="reference (API)" />
　
<meta name="ms.ContentId" content="bff2e900-d262-4601-b279-372d9c531d05" />
　
<meta name="ms.date" content="01/26/2016" />
    <script type="text/javascript" data-do-not-move="true">
        //<![CDATA[
        var AmbientContext = null;
　
        (function () {
            var root = (function () { return this; }).call(null);
　
            var GetCookie = function (name) {
                var cookies = root.document.cookie ? root.document.cookie.split('; ') : [];
                for (var i = 0; i < cookies.length; i++) {
                    var pos = cookies[i].indexOf('=');
                    if (name === root.decodeURIComponent(cookies[i].slice(0, pos))) {
                        var cookie = cookies[i].slice(pos + 1).replace(/\+/g, ' ');
                        cookie = root.decodeURIComponent(cookie);
                        return cookie;
                    }
                }
            };
　
            var JsonDeserialize = function (content) {
                return root.JSON && root.JSON.parse ? root.JSON.parse(content) : (new Function('return (' + content + ')'))();
            };
　
            try {
                AmbientContext = GetCookie('AmbientContext');
                AmbientContext = AmbientContext && JsonDeserialize(AmbientContext);
            } catch (ex) {
            } finally {
                AmbientContext = AmbientContext || null;
            }
        })();
        //]]>
    </script>
　
        <script type="text/javascript" src="https://ajax.aspnetcdn.com/ajax/jQuery/jquery-2.1.0.min.js" data-do-not-move="true" data-provides="jQuery"></script>
    
    
　
　
　
　
　
　
    
　
　
　
　
　
    
　
　
    
    
<link rel="stylesheet" type="text/css" href="https://ajax.aspnetcdn.com/ajax/bootstrap/3.3.6/css/bootstrap.min.css" /><link rel="stylesheet" type="text/css" href="https://i3.int.msdn.microsoft.com/Combined.css?resources=0:MSDNOP,0:OverridesForBootstrap,0:vs,0:OverridesForHighlightJs,1:Tables.MediaQueries,2:OALayout,3:OP_Msdn,4:Header,4:HeaderFooterSprite,4:Header.MediaQueries,5:Banner.MediaQueries,0:OpenPublishingMobileMenu,2:OpenPublishingTopic,0:ImageSprite,4:Footer,4:Footer.MediaQueries,6:StandardRating,2:LinkList,2:OpenPublishingTopic.MediaQueries;/Areas/Epx/Content/Css:0,/Areas/Library/Content:1,/Areas/Epx/Themes/Base/Content:2,/Areas/Library/Themes/Msdn/Content:3,/Areas/Centers/Themes/StandardDevCenter/Content:4,/Areas/Epx/Shared/Content:5,/Areas/Global/Content:6&amp;amp;v=35A471D89007AFF534DF7F93363E8B3E" /></head>
<body class="IE IE10">
    <div id="page">
　
        
　
        
    
　
        
    
　
    
    <link type="text/css" rel="stylesheet" />
    
        
        
    <input type="hidden" id="isHeaderBleeding" value="true" />
    <div id="ux-header" dir="ltr" class="ltr msdn" ms.pgarea="header">
        
　
      <header>
        <span id="singleCol"></span>
        <span id="doubleCol"></span>
        <span id="isMobile"></span>
        <div>
          <div class="row topRow" role="banner">
            <div class="top">
              <div class="left">
                <a class="msdnLogoImg" href="https://int.msdn.microsoft.com/en-us" title="MSDN home" ms.cmpgrp="mslogo">
                  <div class="clip70x15">
                    <img alt="Microsoft Logo" id="msft-logo" class="msft-logo" src="https://i1.int.msdn.microsoft.com/Areas/Centers/Themes/StandardDevCenter/Content/HeaderFooterSprite.png?v=636239072718341861" />
                  </div>
                </a>
                <div class="GrayPipeDiv clip1x18">
                  <img alt="Gray Pipe" class="GrayPipe" src="https://i1.int.msdn.microsoft.com/Areas/Centers/Themes/StandardDevCenter/Content/HeaderFooterSprite.png?v=636239072718341861" />
                </div>
                  <a class="DevCenterFullNameNonMegaBlade" href="https://int.msdn.microsoft.com/en-us">Developer Network</a>
                <a class="DevCenterFullName" href="https://int.msdn.microsoft.com/en-us">Developer Network</a>
                <a class="DevCenterShortName" href="https://int.msdn.microsoft.com/en-us">Developer</a>
              </div>
              <div class="right" ms.cmpgrp="aux nav">
                <div id="signIn" aria-label="Profile button">
　
  <div class="profileImage"></div>
　
　
　
<a class="scarabLink" href="https://login.live.com/login.srf?wa=wsignin1.0&amp;rpsnv=13&amp;ct=1488769637&amp;rver=6.7.6640.0&amp;wp=mcmbi&amp;wlcxt=msdn%24msdn%24msdn&amp;wreply=https%3a%2f%2fint.msdn.microsoft.com%2fen-us%2flibrary%2fazure%2fad%2fgraph%2fapi%2fsigned-in-user-operations&amp;lc=1033&amp;id=254354&amp;mkt=en-us">Sign in</a></div>
　
　
　
　
                <div class="auxNav">
                  <div>
                    <div data-fragmentName="Subscriptions" id="Fragment_Subscriptions" xmlns="http://www.w3.org/1999/xhtml">
  <a href="https://my.visualstudio.com/?wt.mc_id=o~msft~msdn~nav~subscriber&amp;campaign=o~msft~msdn~nav~subscriber" id="Subscriptions_2153_1" xmlns="http://www.w3.org/1999/xhtml">
    <p xmlns="">Subscriber portal</p>
  </a>
</div>
                    <div data-fragmentName="GetTools" id="Fragment_GetTools" xmlns="http://www.w3.org/1999/xhtml">
  <a href="https://www.visualstudio.com/free-developer-offers/" id="GetTools_2153_3" xmlns="http://www.w3.org/1999/xhtml">Get tools</a>
</div>
                  </div>
                </div>
              </div>
            </div>
　
          </div>
          <div class="row middleRow">
            <div class="expandTop">
              <div class="left"></div>
              <div class="right"></div>
            </div>
          </div>
        </div>
        <div id="buttomRowWrapper" class="bg_default">
          <div class="row buttomRow bg_default">
            <div class="bottom">
              <div class="left" role="navigation" aria-label="header toc" ms.cmpgrp="main nav">
                <a id="grip" class="menu-icon" href="javascript:void(0)" role="button" aria-label="navigation menu"></a>
                
                <div id="drawer">
                  <div class="toc">
                    
        <nav>
            <ul class="navL1">
                        <li class="inactive toggle">
                                <a href="javascript:void(0)" role="button" aria-expanded="false">Downloads</a>
                                <ul class="navL2">
                                        <li class="inactive">
　
                                                <a href="https://www.visualstudio.com/downloads/download-visual-studio-vs" role="link" title="Visual Studio">Visual Studio</a>
                                        </li>
                                        <li class="inactive">
　
                                                <a href="https://int.msdn.microsoft.com/microsoft-sdks-msdn" role="link" title="SDKs">SDKs</a>
                                        </li>
                                        <li class="inactive">
　
                                                <a href="https://int.msdn.microsoft.com/evalcenter" role="link" title="Trial software">Trial software</a>
                                        </li>
                                </ul>
                        </li>
                        <li class="inactive toggle">
                                <a href="javascript:void(0)" role="button" aria-expanded="false">Programs</a>
                                <ul class="navL2">
                                        <li class="inactive toggle">
　
                                                <a href="javascript:void(0)" title="Subscriptions" role="button" aria-expanded="false">Subscriptions</a>
                                                <ul class="navL3">
                                                        <li class="inactive">
                                                            <a href="https://int.msdn.microsoft.com/msdn-subscriptions-overview" title="Overview" role="link">Overview</a>
                                                        </li>
                                                        <li class="inactive">
                                                            <a href="https://int.msdn.microsoft.com/msdn-subscriptions-administration" title="Administrators" role="link">Administrators</a>
                                                        </li>
                                                </ul>
                                        </li>
                                        <li class="inactive toggle">
　
                                                <a href="javascript:void(0)" title="Students" role="button" aria-expanded="false">Students</a>
                                                <ul class="navL3">
                                                        <li class="inactive">
                                                            <a href="https://int.msdn.microsoft.com/imagine/imagine-home" title="Microsoft Imagine" role="link">Microsoft Imagine</a>
                                                        </li>
                                                        <li class="inactive">
                                                            <a href="https://int.msdn.microsoft.com/microsoftstudentpartners" title="Microsoft Student Partners" role="link">Microsoft Student Partners</a>
                                                        </li>
                                                </ul>
                                        </li>
                                        <li class="inactive">
　
                                                <a href="https://int.msdn.microsoft.com/applicationbuilder" role="link" title="ISV">ISV</a>
                                        </li>
                                        <li class="inactive">
　
                                                <a href="https://www.microsoft.com/bizspark" role="link" title="Startups">Startups</a>
                                        </li>
                                        <li class="inactive">
　
                                                <a href="https://events.microsoft.com/" role="link" title="Events">Events</a>
                                        </li>
                                </ul>
                        </li>
                        <li class="inactive toggle">
                                <a href="javascript:void(0)" role="button" aria-expanded="false">Community</a>
                                <ul class="navL2">
                                        <li class="inactive">
　
                                                <a href="https://int.msdn.microsoft.com/magazine/dd767791" role="link" title="Magazine">Magazine</a>
                                        </li>
                                        <li class="inactive">
　
                                                <a href="https://social.msdn.microsoft.com/forums/" role="link" title="Forums">Forums</a>
                                        </li>
                                        <li class="inactive">
　
                                                <a href="https://blogs.msdn.microsoft.com/" role="link" title="Blogs">Blogs</a>
                                        </li>
                                        <li class="inactive">
　
                                                <a href="https://channel9.msdn.com/" role="link" title="Channel 9">Channel 9</a>
                                        </li>
                                </ul>
                        </li>
                        <li class="inactive toggle">
                                <a href="javascript:void(0)" role="button" aria-expanded="false">Documentation</a>
                                <ul class="navL2">
                                        <li class="inactive">
　
                                                <a href="https://int.msdn.microsoft.com/library" role="link" title="APIs and reference">APIs and reference</a>
                                        </li>
                                        <li class="inactive">
　
                                                <a href="https://int.msdn.microsoft.com/developer-centers-msdn" role="link" title="Dev centers">Dev centers</a>
                                        </li>
                                        <li class="inactive">
　
                                                <a href="https://ppe.code.msdn.microsoft.com/" role="link" title="Samples">Samples</a>
                                        </li>
                                        <li class="inactive">
　
                                                <a href="https://int.msdn.microsoft.com/retiredcontent" role="link" title="Retired content">Retired content</a>
                                        </li>
                                </ul>
                        </li>
            </ul>
        </nav>
　
                  </div>
                </div>
              </div>
              <div class="right" ms.title="search" role="search">
                <div data-fragmentName="SearchBox" id="Fragment_SearchBox" xmlns="http://www.w3.org/1999/xhtml">
  <div class="SearchBox">
    <form id="HeaderSearchForm" name="HeaderSearchForm" method="get">
      <button id="FakeHeaderSearchButton" value="Search" type="submit" class="header-search-button" role="button" aria-label="search finder">
        <div id="search-finder-div" class="clip16x20">
          <img alt="search finder" id="search-finder" class="search-finder" src="https://i1.int.msdn.microsoft.com/Areas/Centers/Themes/StandardDevCenter/Content/HeaderFooterSprite.png?v=636239072718341861" />
        </div>
      </button>
      <button id="HeaderSearchButton" style="display:none"></button>
      <div id="searchSplitter"></div>
      <div id="searchCloseIconDiv" class="clip16x20" tabindex="0">
        <img alt="search clear" id="searchCloseIcon" class="search-clear-x" src="https://i1.int.msdn.microsoft.com/Areas/Centers/Themes/StandardDevCenter/Content/HeaderFooterSprite.png?v=636239072718341861" />
      </div>
      <div id="searchTextContainer" style="width: 0;">
        <input id="HeaderSearchTextBox" name="query" type="text" aria-label="search edit textbox" maxlength="200" onfocus="Epx.Controls.SearchBox.watermarkFocus(event, this.title)" onblur="Epx.Controls.SearchBox.watermarkBlur(event, this.title)" />
      </div>
    </form>
    
    
  </div>
</div>
              </div>
            </div>
          </div>
        </div>
　
      </header>
　
    </div>
　
    
    
    
    <div id="jumpInfo" style="display: none">We’re sorry. The content you requested has been removed. You’ll be auto redirected in 1 second.</div>
　
　
　
　
　
　
<div id="mobileMenu" data-spy="affix">
    <div id="tocDropdownMenuButton">
        <div class="tocLabel" role="button" tabindex="0">Table of contents<div class="dropDownIcon"></div></div>
        <div id="tocDropdownMenu">
        </div>
    </div>
    <div id="functionDropdownMenuButton">
        <div class="moreToolIcon" aria-label="function area" role="button" tabindex="0"></div>
        <div id="functionDropdownMenu">
        </div>
    </div>
</div>
<div id="mobileMenuSpaceHolder"></div>
<div class="modal fade" id="mobileSocialShareModal">
    <div class="modal-dialog">
        <div class="modal-content">
            <h2 class="modal-title">Shared to</h2>
            <div class="modal-body" id="mobileSocialShare">
            </div>
            <div class="mobileSocialShareModalDialogFooter">
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
            </div>
        </div>
    </div>
</div>
<div class="modal" id="mobileBranchSelectorModal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-body" id="mobileBranchSelector">
            </div>
            <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
        </div>
    </div>
</div>
<div id="tabletContainerWithoutBreadcrumbs"></div>
　
        <div id="body" ms.pgarea="body">
            
　
　
　
　
　
　
<div id="threeColumns">
    <div id="leftColumn" class="left" ms.cmpgrp="left toc">
        <div id="tocNav">
    <div class="tocRootContainer">
        <a href="#" class="tocRoot" title="Table of contents" tabindex="-1">Table of contents</a> 
        <a href="#" class="tocRootIcon" title="Table of contents">+</a>
    </div>
    <div class="tocData">
                <div class="tocUnselected tocLevel1">
                    <div class="tocLevel">
            <a class="tocCollapsed" href="javascript:void(0)" role="button"></a>
            <a href="#" title="Graph API Concepts" class="tocContainer">Graph API Concepts</a>
        </div>
        <div class="tocPadding hidden">
        <div class="tocLevel">
            <a href="https://azure.microsoft.com/documentation/articles/active-directory-graph-api" title="Azure AD Graph API (on Azure.com)">Azure AD Graph API (on Azure.com)</a>
        </div>
        <div class="tocLevel">
            <a href="https://azure.microsoft.com/documentation/articles/active-directory-graph-api-quickstart" title="Quickstart for the Graph API (on Azure.com)">Quickstart for the Graph API (on Azure.com)</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/howto/azure-ad-graph-api-operations-overview" title="Operations overview">Operations overview</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/howto/azure-ad-graph-api-versioning" title="Versioning">Versioning</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/howto/azure-ad-graph-api-permission-scopes" title="Permission scopes">Permission scopes</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/howto/azure-ad-graph-api-supported-queries-filters-and-paging-options" title="Supported queries, filters, and paging options">Supported queries, filters, and paging options</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/howto/azure-ad-graph-api-differential-query" title="Differential query">Differential query</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/howto/azure-ad-graph-api-batch-processing" title="Batch processing">Batch processing</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/howto/azure-ad-graph-api-directory-schema-extensions" title="Directory schema extensions">Directory schema extensions</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/howto/azure-ad-graph-api-throttling" title="Throttling guidance">Throttling guidance</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/howto/azure-ad-graph-api-error-codes-and-error-handling" title="Error codes and error handling">Error codes and error handling</a>
        </div>
        </div>
　
        </div>
        <div class="tocUnselected tocLevel1">
                    <div class="tocLevel">
            <a class="tocCollapsed" href="javascript:void(0)" role="button"></a>
            <a href="#" title="Preview Features" class="tocContainer">Preview Features</a>
        </div>
        <div class="tocPadding hidden">
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/howto/azure-ad-administrative-units-preview" title="Administrative units (preview)">Administrative units (preview)</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/howto/azure-ad-reports-and-events-preview" title="Reports and events (preview)">Reports and events (preview)</a>
        </div>
        <div class="tocLevel">
            <a href="http://blogs.msdn.com/b/aadgraphteam/archive/2015/03/15/full-text-search-capabilities-in-azure-ad-graph-api-preview.aspx" title="Full text search capabilities (preview on Azure AD Graph Team blog)">Full text search capabilities (preview on Azure AD Graph Team blog)</a>
        </div>
        </div>
　
        </div>
        <div class="tocSelected tocLevel1">
                    <div class="tocLevel">
            <a class="tocExpanded" href="javascript:void(0)" role="button"></a>
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/api/api-catalog" title="Graph API Reference" class="">Graph API Reference</a>
        </div>
        <div class="tocPadding">
        <div class="tocLevel current">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/api/signed-in-user-operations" title="Operations on the signed-in user">Operations on the signed-in user</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/api/users-operations" title="Operations on users">Operations on users</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/api/groups-operations" title="Operations on groups">Operations on groups</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/api/contacts-operations" title="Operations on contacts">Operations on contacts</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/api/directoryroles-operations" title="Operations on directory roles">Operations on directory roles</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/api/domains-operations" title="Operations on domains">Operations on domains</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/api/policy-operations" title="Operations on policies">Operations on policies</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/api/functions-and-actions" title="Functions and actions">Functions and actions</a>
        </div>
        <div class="tocLevel">
            <a href="https://int.msdn.microsoft.com/en-us/library/azure/ad/graph/api/entity-and-complex-type-reference" title="Entity and complex type reference">Entity and complex type reference</a>
        </div>
        </div>
　
        </div>
　
    </div>
    <a id="tocMenuToggler" role="button" href="javascript:void(0);">
        <span id="tocMenuTogglerIcon" role="button" aria-expanded="true" aria-label="Table of contents menu"></span>
        <div id="tocMenuTogglerLabel">TOC</div>
    </a>
</div>
　
　
　
        <div style="display:none">
            <div id="CollapseLocalizeString">Collapse the table of content</div>
            <div id="ExpandLocalizeString">Expand the table of content</div>
        </div>
    </div>
    <div class="main" ms.cmpgrp="content body">
        <div id="oaContent" class="row"><div class="col-md-9" id="api-doc-contents"><h1 id="operations-on-the-signed-in-user--graph-api-reference">Operations on the signed-in user | Graph API reference</h1><span><div class="gitContributors"><span class="author-bio"><a target="_blank" href="https://github.com/JimacoMS" aria-label="Jimaco Brannian"><span class="author-img" style="background-image:url('https://avatars.githubusercontent.com/u/8431909?v=3&amp;s=50')"></span></a></span><span class="username"><a target="_blank" href="https://github.com/JimacoMS">Jimaco Brannian</a></span><span class="contributorSplitter">|</span><span class="contributorsLabel">Last Updated: 8/26/2016</span><div id="contributorList"><span class="contributorSplitter">|</span><div class="contributors"><span class="contributorsLabel">1 Contributor</span><ul><li><a target="_blank" href="https://github.com/PatAltimore" aria-label="Pat Altimore"><span class="contributor-img" style="background-image:url('https://avatars.githubusercontent.com/u/17440249?v=3&amp;s=25')"></span></a></li></ul></div></div></div></span><p><em><strong>Applies to:</strong> Graph API | Azure Active Directory</em></p><p><a id="Overview"></a>
This topic discusses how to perform operations on the signed-in user with the Azure Active Directory (AD) Graph API by using the <code>me</code> alias. With the Azure AD Graph API, you can read and update properties of the signed-in user. You can also query and modify a the signed-in user's relationships to other directory entities. For example, you  can assign the signed-in user's manager, query the user's direct reports, manage group memberships, app roles, and devices assigned to the user, and much more.</p><p>The Graph API is an OData 3.0 compliant REST API that provides programmatic access to directory objects in Azure Active Directory, such as users, groups, organizational contacts, and applications.</p><div class="IMPORTANT"><h5>Important</h5><p>Azure AD Graph API functionality is also available through <a href="https://graph.microsoft.io/">Microsoft Graph</a>, a unified API that also includes APIs from other Microsoft services like Outlook, OneDrive, OneNote, Planner, and Office Graph, all accessed through a single endpoint with a single access token.</p></div><h2 id="Signed-in_User">Performing REST operations on the signed-in user </h2><p>You can use the <code>me</code> alias to target the signed-in user. To perform operations on the signed-in user with the Graph API, you send HTTP requests with a supported method (GET, POST, PATCH, PUT, or DELETE) to an endpoint that uses the <code>me</code> alias to target the signed-in user, a navigation property of the user, or a function or action that can be called on the user.</p><p>Graph API requests use the following basic URL:</p><pre><code class="lang-no-highlight">https://graph.windows.net/{tenant_id}/{resource_path}?{api_version}[odata_query_parameters]
</code></pre><div class="IMPORTANT"><h5>Important</h5><p>Requests sent to the Graph API must be well-formed, target a valid endpoint and version of the Graph API, and carry a valid access token obtained from Azure AD in their <code>Authorization</code> header. For more detailed information about creating requests and receiving responses with the Graph API, see <a href="../howto/azure-ad-graph-api-operations-overview">Operations Overview</a>.</p></div><p>You use can use the <code>me</code> alias to target the signed-in user. This alias replaces the <code>{tenant id}</code> and <code>{resource path}</code> segments in the request URL. When you send a request to the Graph API with the <code>me</code> alias, it derives the tenant and user from the bearer token attached to the request. For example, sending a GET request to <code>https://graph.windows.net/me?api-version=1.6</code> will return the user object of the signed-in user.</p><p>You specify the URL differently depending on whether you are targeting the signed-in user or one of its navigation properties. </p><ul><li><code>me</code> targets the signed-in user. You can use this resource path to get the declared properties of the user and to modify the declared properties of the user. </li><li><code>me/{nav_property}</code> targets the specified navigation property of the signed-in user. You can use it to return the object or objects referenced by the target navigation property of the user. <strong>Note</strong>: This form of addressing is only available for reads. </li><li><code>me/$links/{nav_property}</code> targets the specified navigation property of the signed-in user. You can use this form of addressing to both read and modify a navigation property. On reads, the objects referenced by the property are returned as one or more links in the response body. On writes, the objects are specified as one or more links in the request body. </li></ul><p>For example, the following request returns a link to the signed-in user's manager:</p><pre><code class="lang-no-highlight">GET https://graph.windows.net/me/$links/manager?api-version=1.6
</code></pre><hr /><h2 id="BasicOperations">Basic operations on the signed-in user </h2><p>You can read the signed-in user and update its declared properties by using the <code>me</code> alias. The following topics show you how.</p><hr /><h3 id="GetMe">Get the signed-in user </h3><p>Gets the signed-in user.</p><p>On success, returns the <a href="entity-and-complex-type-reference#user-entity">User</a> object for the signed-in user; otherwise, the response body contains error details. For more information about errors, see <a href="../howto/azure-ad-graph-api-error-codes-and-error-handling">Error Codes and Error Handling</a>.</p><section data-operation="get me" class="operationDocs sampleRequestAndResponseBlock"><h4>Request</h4><pre><code class="request no-highlight"><span class="label label-success">GET</span><span class="url"> https://graph.windows.net/me?api-version</span></code></pre><div class="tryItArea"><div class="apiDetails"><input type="hidden" class="isInteractive" value="true" /><input type="hidden" class="methodType" value="GET" /><input type="hidden" class="urlToSend" value="https://graph.windows.net/me?api-version" /><h4>Parameters</h4><table class="table table-condensed"><thead><tr><th>Parameter</th><th>Type</th><th class="default">Value</th><th>Notes</th></tr></thead><tbody><tr><td colspan="4"><i>Query</i></td></tr><tr><td>api-version</td><td>string</td><td class="default"><input data-param="api-version" data-isqueryparam="true" value="1.6" /></td><td>Specifies the version of the Graph API to target. Beginning with version 1.5, the api-version string is represented in major.minor format. Prior releases were represented as date strings: '2013-11-08' and '2013-04-05'. Required.</td></tr></tbody></table></div></div><div class="requestToUpdate"><h4>Requested URL</h4><pre><code class="request no-highlight"><span class="label label-success">GET</span><span class="url"> https://graph.windows.net/me?api-version</span></code></pre></div><div class="responseList"><h4>Response</h4><div class="codeexample response"><div class="statusCode">
                        Status Code:<span class="status">200</span></div><div class="contentType"><span>Content-Type:</span><ul role="tablist"><li class="active" data-interactive="true">
application/json
                                </li></ul></div><div class="tab-content"><div class="tab-pane active" id="get_me0" data-interactive="true"><div class="tabbedCodeSnippets"><ul class="nav nav-tabs" role="tablist"><li class="active"><a role="tabpanel" data-toggle="tab" href="#body_get_me0">Body</a></li><li class="responseHeader" style="display:none"><a role="tabpanel" data-toggle="tab" href="#headers_get_me0">Headers</a></li></ul><div class="tab-content"><div class="tab-pane active" id="body_get_me0"><pre><code class="lang-js">{
  "odata.metadata": "https://graph.windows.net/myorganization/$metadata#directoryObjects/Microsoft.DirectoryServices.User/@Element",
  "odata.type": "Microsoft.DirectoryServices.User",
  "objectType": "User",
  "objectId": "13addec1-c5ae-47f5-a1fe-202be14b1570",
  "deletionTimestamp": null,
  "accountEnabled": true,
  "signInNames": [],
  "assignedLicenses": [
    {
      "disabledPlans": [],
      "skuId": "6fd2c87f-b296-42f0-b197-1e91e994b900"
    }
  ],
  "assignedPlans": [
    {
      "assignedTimestamp": "2014-10-14T02:54:04Z",
      "capabilityStatus": "Enabled",
      "service": "exchange",
      "servicePlanId": "efb87545-963c-4e0d-99df-69c6916d9eb0"
    },
    {
      "assignedTimestamp": "2014-10-14T02:54:04Z",
      "capabilityStatus": "Enabled",
      "service": "SharePoint",
      "servicePlanId": "5dbe027f-2339-4123-9542-606e4d348a72"
    },
    {
      "assignedTimestamp": "2014-10-14T02:54:04Z",
      "capabilityStatus": "Enabled",
      "service": "SharePoint",
      "servicePlanId": "e95bec33-7c88-4a70-8e19-b10bd9d0c014"
    },
    {
      "assignedTimestamp": "2014-10-14T02:54:04Z",
      "capabilityStatus": "Enabled",
      "service": "MicrosoftCommunicationsOnline",
      "servicePlanId": "0feaeb32-d00e-4d66-bd5a-43b5b83db82c"
    },
    {
      "assignedTimestamp": "2014-10-14T02:54:04Z",
      "capabilityStatus": "Enabled",
      "service": "MicrosoftOffice",
      "servicePlanId": "43de0ff5-c92c-492b-9116-175376d08c38"
    },
    {
      "assignedTimestamp": "2014-10-14T02:54:04Z",
      "capabilityStatus": "Enabled",
      "service": "RMSOnline",
      "servicePlanId": "bea4c11e-220a-4e6d-8eb8-8ea15d019f90"
    }
  ],
  "city": "Tulsa",
  "country": "United States",
  "creationType": null,
  "department": "Sales &amp; Marketing",
  "dirSyncEnabled": null,
  "displayName": "Garth Fort",
  "facsimileTelephoneNumber": null,
  "givenName": "Garth",
  "immutableId": null,
  "jobTitle": "Web Marketing Manager",
  "lastDirSyncTime": null,
  "mail": "garthf@a830edad9050849NDA1.onmicrosoft.com",
  "mailNickname": "garthf",
  "mobile": null,
  "onPremisesSecurityIdentifier": null,
  "otherMails": [],
  "passwordPolicies": "None",
  "passwordProfile": null,
  "physicalDeliveryOfficeName": "20/1101",
  "postalCode": "74133",
  "preferredLanguage": "en-US",
  "provisionedPlans": [
    {
      "capabilityStatus": "Enabled",
      "provisioningStatus": "Success",
      "service": "exchange"
    },
    {
      "capabilityStatus": "Enabled",
      "provisioningStatus": "Success",
      "service": "MicrosoftCommunicationsOnline"
    },
    {
      "capabilityStatus": "Enabled",
      "provisioningStatus": "Success",
      "service": "SharePoint"
    },
    {
      "capabilityStatus": "Enabled",
      "provisioningStatus": "Success",
      "service": "SharePoint"
    },
    {
      "capabilityStatus": "Enabled",
      "provisioningStatus": "Success",
      "service": "MicrosoftOffice"
    }
  ],
  "provisioningErrors": [],
  "proxyAddresses": [
    "SMTP:garthf@a830edad9050849NDA1.onmicrosoft.com"
  ],
  "sipProxyAddress": "garthf@a830edad9050849NDA1.onmicrosoft.com",
  "state": "OK",
  "streetAddress": "7633 E. 63rd Place, Suite 300",
  "surname": "Fort",
  "telephoneNumber": "+1 918 555 0101",
  "usageLocation": "US",
  "userPrincipalName": "garthf@a830edad9050849NDA1.onmicrosoft.com",
  "userType": "Member"
}</code></pre></div><div class="tab-pane" id="headers_get_me0"><pre><code class="lang-js http"></code></pre></div></div></div></div></div></div><h4>Response List</h4><table class="responseTable"><thead><tr><th>Status Code</th><th>Description</th></tr></thead><tbody><tr><td>200</td><td>OK. Indicates success. The signed-in user is returned in the response body.</td></tr></tbody></table></div><div class="tabbedCodeSnippets"><h4>Code Samples</h4><ul class="nav nav-tabs" role="tablist"><li class="active"><a role="tab" data-toggle="tab" href="#CSharp_getme">C#</a></li><li class=""><a role="tab" data-toggle="tab" href="#CURL_getme">Curl</a></li><li class=""><a role="tab" data-toggle="tab" href="#Java_getme">Java</a></li><li class=""><a role="tab" data-toggle="tab" href="#JS_getme">JavaScript</a></li><li class=""><a role="tab" data-toggle="tab" href="#ObjC_getme">ObjC</a></li><li class=""><a role="tab" data-toggle="tab" href="#PHP_getme">PHP</a></li><li class=""><a role="tab" data-toggle="tab" href="#PYTHON_getme">Python</a></li><li class=""><a role="tab" data-toggle="tab" href="#RUBY_getme">Ruby</a></li></ul><div class="tab-content"><div class="tab-pane active" id="CSharp_getme"><pre><code class="c#">
using System;
using System.Net.Http.Headers;
using System.Text;
using System.Net.Http;
using System.Web;
　
namespace CSHttpClientSample
{
    static class Program
    {
	    static void Main()
        {
            MakeRequest();
　
            Console.WriteLine("Hit ENTER to exit...");
            Console.ReadLine();
        }
　
        static async void MakeRequest()
        {
            var client = new HttpClient();
            var queryString = HttpUtility.ParseQueryString(string.Empty);
　
            /* OAuth2 is required to access this API. For more information visit:
               https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks */
　
　
　
		   // Specify values for the following required parameters
			queryString["api-version"] = "1.6";
            // Specify values for path parameters (shown as {...})
            var uri = "https://graph.windows.net/me?" + queryString;
　
　
            var response = await client.GetAsync(uri);
　
            if (response.Content != null)
            {
                var responseString = await response.Content.ReadAsStringAsync();
                Console.WriteLine(responseString);
            }
        }
    }
}
</code></pre></div><div class="tab-pane" id="CURL_getme"><pre><code class="curl">@ECHO OFF
　
REM OAuth2 is required to access this API. For more information visit: https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
REM Specify values for path parameters (shown as {...}), values for query parameters
curl -v -X GET "https://graph.windows.net/me?api-version=1.6&amp;amp;"^
　
</code></pre></div><div class="tab-pane" id="Java_getme"><pre><code class="java">// This sample uses the Apache HTTP client from HTTP Components (http://hc.apache.org/httpcomponents-client-ga/)
import java.net.URI;
　
import org.apache.http.HttpEntity;
import org.apache.http.HttpResponse;
import org.apache.http.client.HttpClient;
import org.apache.http.client.methods.HttpGet;
import org.apache.http.client.utils.URIBuilder;
import org.apache.http.impl.client.HttpClients;
import org.apache.http.util.EntityUtils;
　
public class JavaSample {
　
  public static void main(String[] args) {
	HttpClient httpclient = HttpClients.createDefault();
　
	try
	{
		// OAuth2 is required to access this API. For more information visit:
		// https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
		// Specify values for path parameters (shown as {...})
		URIBuilder builder = new URIBuilder("https://graph.windows.net/me");
		// Specify values for the following required parameters
		builder.setParameter("api-version", "1.6");
		URI uri = builder.build();
		HttpGet request = new HttpGet(uri);
		HttpResponse response = httpclient.execute(request);
		HttpEntity entity = response.getEntity();
		if (entity != null) {
			System.out.println(EntityUtils.toString(entity));
		}
	}
	catch (Exception e)
	{
		System.out.println(e.getMessage());
	}
  }
}</code></pre></div><div class="tab-pane" id="JS_getme"><pre><code class="javascript">
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
&lt;title&gt;JSSample&lt;/title&gt;
&lt;script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js"&gt;&lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;script type="text/javascript"&gt;
	$(function() {
		// OAuth2 is required to access this API. For more information visit:
		// https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
		var params = {
			// Specify values for the following required parameters
			'api-version': "1.6",
		};
		
		$.ajax({
			// Specify values for path parameters (shown as {...})
			url: 'https://graph.windows.net/me?' + $.param(params),
			type: 'GET',
		})
		.done(function(data) {
			alert("success");
		})
		.fail(function() {
			alert("error");
		});
	});
&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
</code></pre></div><div class="tab-pane" id="ObjC_getme"><pre><code class="objc">
#import &lt;Foundation/Foundation.h&gt;
　
int main(int argc, const char * argv[])
{
    NSAutoreleasePool * pool = [[NSAutoreleasePool alloc] init];
    
	// OAuth2 is required to access this API. For more information visit:
	// https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
	// Specify values for path parameters (shown as {...})
    NSString* path = @"https://graph.windows.net/me";
    NSArray* array = @[
                         @"entities=true",
                      ];
    
    NSString* string = [array componentsJoinedByString:@"&amp;"];
    path = [path stringByAppendingFormat:@"?%@", string];
    NSLog(@"%@", path);
　
    NSMutableURLRequest* _request = [NSMutableURLRequest requestWithURL:[NSURL URLWithString:path]];
    [_request setHTTPMethod:@"GET"];
    
    NSURLResponse *response = nil;
    NSError *error = nil;
    NSData* _connectionData = [NSURLConnection sendSynchronousRequest:_request returningResponse:&amp;response error:&amp;error];
    if(nil != error)
    {
        NSLog(@"Error: %@", error);
    }
    else
    {
        NSError* error = nil;
        NSMutableDictionary* json = nil;
        
        NSString* dataString = [[NSString alloc] initWithData:_connectionData encoding:NSUTF8StringEncoding];
        NSLog(@"%@", dataString);
        
        if(nil != _connectionData)
        {
            json = [NSJSONSerialization JSONObjectWithData:_connectionData options:NSJSONReadingMutableContainers error:&amp;error];
        }
        
        if (error || !json)
        {
            NSLog(@"Could not parse loaded json with error:%@", error);
        }
        
        NSLog(@"%@", json);
        _connectionData = nil;
    }
    
    [pool drain];
    return 0;
}
</code></pre></div><div class="tab-pane" id="PHP_getme"><pre><code class="php">&lt;?php
　
// This sample uses the pecl_http package. (for more information: http://pecl.php.net/package/pecl_http)
require_once 'HTTP/Request2.php';
$headers = array(
);
　
$query_params = array(
	// Specify values for the following required parameters
	'api-version' =&gt; '1.6',
);
　
$request = new Http_Request2('https://graph.windows.net/me');
$request-&gt;setMethod(HTTP_Request2::METHOD_GET);
$request-&gt;setHeader($headers);
　
// OAuth2 is required to access this API. For more information visit:
// https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
$url = $request-&gt;getUrl();
$url-&gt;setQueryVariables($query_params);
　
try
{
	$response = $request-&gt;send();
	
	echo $response-&gt;getBody();
}
catch (HttpException $ex)
{
	echo $ex;
}
　
?&gt;</code></pre></div><div class="tab-pane" id="PYTHON_getme"><pre><code class="python">
########### Python 2.7 #############
import httplib, urllib, base64
　
# OAuth2 is required to access this API. For more information visit: https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
headers = {
}
　
params = urllib.urlencode({
	# Specify values for the following required parameters
	'api-version': '1.6',
})
　
try:
	conn = httplib.HTTPSConnection('graph.windows.net')
	# Specify values for path parameters (shown as {...}) and request body if needed
	conn.request("GET", "/me?%s" % params, "", headers)
	response = conn.getresponse()
	data = response.read()
	print(data)
	conn.close()
except Exception as e:
	print("[Errno {0}] {1}".format(e.errno, e.strerror))
　
####################################
　
########### Python 3.2 #############
import http.client, urllib.request, urllib.parse, urllib.error, base64
　
# OAuth2 is required to access this API. For more information visit: https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
headers = {
}
　
params = urllib.parse.urlencode({
	# Specify values for the following required parameters
	'api-version': '1.6',
})
　
try:
	conn = http.client.HTTPSConnection('graph.windows.net')
	# Specify values for path parameters (shown as {...}) and request body if needed
	conn.request("GET", "/me?%s" % params, "", headers)
	response = conn.getresponse()
	data = response.read()
	print(data)
	conn.close()
except Exception as e:
	print("[Errno {0}] {1}".format(e.errno, e.strerror))
　
####################################</code></pre></div><div class="tab-pane" id="RUBY_getme"><pre><code class="ruby">require 'net/http'
　
uri = URI('https://graph.windows.net/me')
　
uri.query = URI.encode_www_form({
	# Specify values for the following required parameters
	'api-version' =&gt; '1.6',
})
　
request = Net::HTTP::Get.new(uri.request_uri)
　
# OAuth2 is required to access this API. For more information visit: https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
　
　
response = Net::HTTP.start(uri.host, uri.port, :use_ssl =&gt; uri.scheme == 'https') do |http|
    http.request(request)
end
　
puts response.body</code></pre></div></div></div></section><hr /><h3 id="UpdateMe">Update the signed-in user </h3><p>Updates properties of the signed-in user. Specify any writable <a href="entity-and-complex-type-reference#user-entity">User</a> property in the request body. Only the properties that you specify are changed.</p><p>On success, no response body is returned; otherwise, the response body contains error details. For more information about errors, see <a href="../howto/azure-ad-graph-api-error-codes-and-error-handling">Error Codes and Error Handling</a>.</p><section data-operation="update me" class="operationDocs sampleRequestAndResponseBlock"><h4>Request</h4><pre><code class="request no-highlight"><span class="label label-warning">PATCH</span><span class="url"> https://graph.windows.net/me[?api-version]</span></code></pre><div class="tryItArea"><div class="apiDetails"><input type="hidden" class="methodType" value="PATCH" /><input type="hidden" class="urlToSend" value="https://graph.windows.net/me[?api-version]" /><h4>Parameters</h4><table class="table table-condensed"><thead><tr><th>Parameter</th><th>Type</th><th class="default">Value</th><th>Notes</th></tr></thead><tbody><tr><td colspan="4"><i>Query</i></td></tr><tr><td>api-version</td><td>string</td><td class="default"><input data-param="api-version" data-isqueryparam="true" value="1.6" /></td><td>Specifies the version of the Graph API to target. Beginning with version 1.5, the api-version string is represented in major.minor format. Prior releases were represented as date strings: '2013-11-08' and '2013-04-05'. Required.</td></tr><tr><td colspan="4" class="bodyParameterHeading"><i>Body</i></td></tr><tr><td colspan="4">
                                
　
Content-Type: application/json
<pre><code class="lang-js">{
  "department": "Sales",
  "usageLocation": "US"
}</code></pre></td></tr></tbody></table></div></div><div class="requestToUpdate"><h4>Requested URL</h4><pre><code class="request no-highlight"><span class="label label-warning">PATCH</span><span class="url"> https://graph.windows.net/me[?api-version]</span></code></pre></div><div class="responseList"><h4>Response</h4><div class="codeexample response"><div class="statusCode">
                        Status Code:<span class="status">204</span></div><div class="contentType"><span>Content-Type:</span><ul role="tablist"><li class="active" data-interactive="true">
application/json
                                </li></ul></div><div class="tab-content"><div class="tab-pane active" id="update_me0" data-interactive="true"><div class="tabbedCodeSnippets"><ul class="nav nav-tabs" role="tablist"><li class="active"><a role="tabpanel" data-toggle="tab" href="#body_update_me0">Body</a></li><li class="responseHeader" style="display:none"><a role="tabpanel" data-toggle="tab" href="#headers_update_me0">Headers</a></li></ul><div class="tab-content"><div class="tab-pane active" id="body_update_me0"><pre><code class="lang-js">none</code></pre></div><div class="tab-pane" id="headers_update_me0"><pre><code class="lang-js http"></code></pre></div></div></div></div></div></div><h4>Response List</h4><table class="responseTable"><thead><tr><th>Status Code</th><th>Description</th></tr></thead><tbody><tr><td>204</td><td>No Content. Indicates success. No response body is returned.</td></tr></tbody></table></div></section><hr /><h2 id="NavigationOps">Operations on navigation properties </h2><p>Relationships between a user and other objects in the directory such as the user's manager, direct group memberships, and direct reports are exposed through navigation properties. When you use the <code>me</code> alias, you can read and, in some cases, modify these relationships by targeting these navigation properties in your requests.</p><hr /><h3 id="GetMyManagerObject">Get the signed-in user's manager (object) </h3><p>Gets the signed-in user's manager (object) from the <strong>manager</strong> navigation property.</p><p>On success, returns the <a href="entity-and-complex-type-reference#user-entity">User</a> or <a href="entity-and-complex-type-reference#contact-entity">Contact</a> assigned as the user's manager; otherwise, the response body contains error details. For more information about errors, see <a href="../howto/azure-ad-graph-api-error-codes-and-error-handling">Error Codes and Error Handling</a>.</p><p>Returns <strong>404 Not Found</strong> if the user does not have a manager assigned.</p><section data-operation="get my manager object" class="operationDocs sampleRequestAndResponseBlock"><h4>Request</h4><pre><code class="request no-highlight"><span class="label label-success">GET</span><span class="url"> https://graph.windows.net/me/manager?api-version</span></code></pre><div class="tryItArea"><div class="apiDetails"><input type="hidden" class="isInteractive" value="true" /><input type="hidden" class="methodType" value="GET" /><input type="hidden" class="urlToSend" value="https://graph.windows.net/me/manager?api-version" /><h4>Parameters</h4><table class="table table-condensed"><thead><tr><th>Parameter</th><th>Type</th><th class="default">Value</th><th>Notes</th></tr></thead><tbody><tr><td colspan="4"><i>Query</i></td></tr><tr><td>api-version</td><td>string</td><td class="default"><input data-param="api-version" data-isqueryparam="true" value="1.6" /></td><td>Specifies the version of the Graph API to target. Beginning with version 1.5, the api-version string is represented in major.minor format. Prior releases were represented as date strings: '2013-11-08' and '2013-04-05'. Required.</td></tr></tbody></table></div></div><div class="requestToUpdate"><h4>Requested URL</h4><pre><code class="request no-highlight"><span class="label label-success">GET</span><span class="url"> https://graph.windows.net/me/manager?api-version</span></code></pre></div><div class="responseList"><h4>Response</h4><div class="codeexample response"><div class="statusCode">
                        Status Code:<span class="status">200</span></div><div class="contentType"><span>Content-Type:</span><ul role="tablist"><li class="active" data-interactive="true">
application/json
                                </li></ul></div><div class="tab-content"><div class="tab-pane active" id="get_my_manager_object0" data-interactive="true"><div class="tabbedCodeSnippets"><ul class="nav nav-tabs" role="tablist"><li class="active"><a role="tabpanel" data-toggle="tab" href="#body_get_my_manager_object0">Body</a></li><li class="responseHeader" style="display:none"><a role="tabpanel" data-toggle="tab" href="#headers_get_my_manager_object0">Headers</a></li></ul><div class="tab-content"><div class="tab-pane active" id="body_get_my_manager_object0"><pre><code class="lang-js">{
  "odata.metadata": "https://graph.windows.net/myorganization/$metadata#directoryObjects/Microsoft.DirectoryServices.User/@Element",
  "odata.type": "Microsoft.DirectoryServices.User",
  "objectType": "User",
  "objectId": "13addec1-c5ae-47f5-a1fe-202be14b1570",
  "deletionTimestamp": null,
  "accountEnabled": true,
  "signInNames": [],
  "assignedLicenses": [
    {
      "disabledPlans": [],
      "skuId": "6fd2c87f-b296-42f0-b197-1e91e994b900"
    }
  ],
  "assignedPlans": [
    {
      "assignedTimestamp": "2014-10-14T02:54:04Z",
      "capabilityStatus": "Enabled",
      "service": "exchange",
      "servicePlanId": "efb87545-963c-4e0d-99df-69c6916d9eb0"
    },
    {
      "assignedTimestamp": "2014-10-14T02:54:04Z",
      "capabilityStatus": "Enabled",
      "service": "SharePoint",
      "servicePlanId": "5dbe027f-2339-4123-9542-606e4d348a72"
    },
    {
      "assignedTimestamp": "2014-10-14T02:54:04Z",
      "capabilityStatus": "Enabled",
      "service": "SharePoint",
      "servicePlanId": "e95bec33-7c88-4a70-8e19-b10bd9d0c014"
    },
    {
      "assignedTimestamp": "2014-10-14T02:54:04Z",
      "capabilityStatus": "Enabled",
      "service": "MicrosoftCommunicationsOnline",
      "servicePlanId": "0feaeb32-d00e-4d66-bd5a-43b5b83db82c"
    },
    {
      "assignedTimestamp": "2014-10-14T02:54:04Z",
      "capabilityStatus": "Enabled",
      "service": "MicrosoftOffice",
      "servicePlanId": "43de0ff5-c92c-492b-9116-175376d08c38"
    },
    {
      "assignedTimestamp": "2014-10-14T02:54:04Z",
      "capabilityStatus": "Enabled",
      "service": "RMSOnline",
      "servicePlanId": "bea4c11e-220a-4e6d-8eb8-8ea15d019f90"
    }
  ],
  "city": "Tulsa",
  "country": "United States",
  "creationType": null,
  "department": "Sales &amp; Marketing",
  "dirSyncEnabled": null,
  "displayName": "Garth Fort",
  "facsimileTelephoneNumber": null,
  "givenName": "Garth",
  "immutableId": null,
  "jobTitle": "Web Marketing Manager",
  "lastDirSyncTime": null,
  "mail": "garthf@a830edad9050849NDA1.onmicrosoft.com",
  "mailNickname": "garthf",
  "mobile": null,
  "onPremisesSecurityIdentifier": null,
  "otherMails": [],
  "passwordPolicies": "None",
  "passwordProfile": null,
  "physicalDeliveryOfficeName": "20/1101",
  "postalCode": "74133",
  "preferredLanguage": "en-US",
  "provisionedPlans": [
    {
      "capabilityStatus": "Enabled",
      "provisioningStatus": "Success",
      "service": "exchange"
    },
    {
      "capabilityStatus": "Enabled",
      "provisioningStatus": "Success",
      "service": "MicrosoftCommunicationsOnline"
    },
    {
      "capabilityStatus": "Enabled",
      "provisioningStatus": "Success",
      "service": "SharePoint"
    },
    {
      "capabilityStatus": "Enabled",
      "provisioningStatus": "Success",
      "service": "SharePoint"
    },
    {
      "capabilityStatus": "Enabled",
      "provisioningStatus": "Success",
      "service": "MicrosoftOffice"
    }
  ],
  "provisioningErrors": [],
  "proxyAddresses": [
    "SMTP:garthf@a830edad9050849NDA1.onmicrosoft.com"
  ],
  "sipProxyAddress": "garthf@a830edad9050849NDA1.onmicrosoft.com",
  "state": "OK",
  "streetAddress": "7633 E. 63rd Place, Suite 300",
  "surname": "Fort",
  "telephoneNumber": "+1 918 555 0101",
  "usageLocation": "US",
  "userPrincipalName": "garthf@a830edad9050849NDA1.onmicrosoft.com",
  "userType": "Member"
}</code></pre></div><div class="tab-pane" id="headers_get_my_manager_object0"><pre><code class="lang-js http"></code></pre></div></div></div></div></div></div><h4>Response List</h4><table class="responseTable"><thead><tr><th>Status Code</th><th>Description</th></tr></thead><tbody><tr><td>200</td><td>OK. Indicates success. The signed-in user's manager is returned.</td></tr></tbody></table></div><div class="tabbedCodeSnippets"><h4>Code Samples</h4><ul class="nav nav-tabs" role="tablist"><li class="active"><a role="tab" data-toggle="tab" href="#CSharp_getmymanagerobject">C#</a></li><li class=""><a role="tab" data-toggle="tab" href="#CURL_getmymanagerobject">Curl</a></li><li class=""><a role="tab" data-toggle="tab" href="#Java_getmymanagerobject">Java</a></li><li class=""><a role="tab" data-toggle="tab" href="#JS_getmymanagerobject">JavaScript</a></li><li class=""><a role="tab" data-toggle="tab" href="#ObjC_getmymanagerobject">ObjC</a></li><li class=""><a role="tab" data-toggle="tab" href="#PHP_getmymanagerobject">PHP</a></li><li class=""><a role="tab" data-toggle="tab" href="#PYTHON_getmymanagerobject">Python</a></li><li class=""><a role="tab" data-toggle="tab" href="#RUBY_getmymanagerobject">Ruby</a></li></ul><div class="tab-content"><div class="tab-pane active" id="CSharp_getmymanagerobject"><pre><code class="c#">
using System;
using System.Net.Http.Headers;
using System.Text;
using System.Net.Http;
using System.Web;
　
namespace CSHttpClientSample
{
    static class Program
    {
	    static void Main()
        {
            MakeRequest();
　
            Console.WriteLine("Hit ENTER to exit...");
            Console.ReadLine();
        }
　
        static async void MakeRequest()
        {
            var client = new HttpClient();
            var queryString = HttpUtility.ParseQueryString(string.Empty);
　
            /* OAuth2 is required to access this API. For more information visit:
               https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks */
　
　
　
		   // Specify values for the following required parameters
			queryString["api-version"] = "1.6";
            // Specify values for path parameters (shown as {...})
            var uri = "https://graph.windows.net/me/manager?" + queryString;
　
　
            var response = await client.GetAsync(uri);
　
            if (response.Content != null)
            {
                var responseString = await response.Content.ReadAsStringAsync();
                Console.WriteLine(responseString);
            }
        }
    }
}
</code></pre></div><div class="tab-pane" id="CURL_getmymanagerobject"><pre><code class="curl">@ECHO OFF
　
REM OAuth2 is required to access this API. For more information visit: https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
REM Specify values for path parameters (shown as {...}), values for query parameters
curl -v -X GET "https://graph.windows.net/me/manager?api-version=1.6&amp;amp;"^
　
</code></pre></div><div class="tab-pane" id="Java_getmymanagerobject"><pre><code class="java">// This sample uses the Apache HTTP client from HTTP Components (http://hc.apache.org/httpcomponents-client-ga/)
import java.net.URI;
　
import org.apache.http.HttpEntity;
import org.apache.http.HttpResponse;
import org.apache.http.client.HttpClient;
import org.apache.http.client.methods.HttpGet;
import org.apache.http.client.utils.URIBuilder;
import org.apache.http.impl.client.HttpClients;
import org.apache.http.util.EntityUtils;
　
public class JavaSample {
　
  public static void main(String[] args) {
	HttpClient httpclient = HttpClients.createDefault();
　
	try
	{
		// OAuth2 is required to access this API. For more information visit:
		// https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
		// Specify values for path parameters (shown as {...})
		URIBuilder builder = new URIBuilder("https://graph.windows.net/me/manager");
		// Specify values for the following required parameters
		builder.setParameter("api-version", "1.6");
		URI uri = builder.build();
		HttpGet request = new HttpGet(uri);
		HttpResponse response = httpclient.execute(request);
		HttpEntity entity = response.getEntity();
		if (entity != null) {
			System.out.println(EntityUtils.toString(entity));
		}
	}
	catch (Exception e)
	{
		System.out.println(e.getMessage());
	}
  }
}</code></pre></div><div class="tab-pane" id="JS_getmymanagerobject"><pre><code class="javascript">
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
&lt;title&gt;JSSample&lt;/title&gt;
&lt;script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js"&gt;&lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;script type="text/javascript"&gt;
	$(function() {
		// OAuth2 is required to access this API. For more information visit:
		// https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
		var params = {
			// Specify values for the following required parameters
			'api-version': "1.6",
		};
		
		$.ajax({
			// Specify values for path parameters (shown as {...})
			url: 'https://graph.windows.net/me/manager?' + $.param(params),
			type: 'GET',
		})
		.done(function(data) {
			alert("success");
		})
		.fail(function() {
			alert("error");
		});
	});
&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
</code></pre></div><div class="tab-pane" id="ObjC_getmymanagerobject"><pre><code class="objc">
#import &lt;Foundation/Foundation.h&gt;
　
int main(int argc, const char * argv[])
{
    NSAutoreleasePool * pool = [[NSAutoreleasePool alloc] init];
    
	// OAuth2 is required to access this API. For more information visit:
	// https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
	// Specify values for path parameters (shown as {...})
    NSString* path = @"https://graph.windows.net/me/manager";
    NSArray* array = @[
                         @"entities=true",
                      ];
    
    NSString* string = [array componentsJoinedByString:@"&amp;"];
    path = [path stringByAppendingFormat:@"?%@", string];
    NSLog(@"%@", path);
　
    NSMutableURLRequest* _request = [NSMutableURLRequest requestWithURL:[NSURL URLWithString:path]];
    [_request setHTTPMethod:@"GET"];
    
    NSURLResponse *response = nil;
    NSError *error = nil;
    NSData* _connectionData = [NSURLConnection sendSynchronousRequest:_request returningResponse:&amp;response error:&amp;error];
    if(nil != error)
    {
        NSLog(@"Error: %@", error);
    }
    else
    {
        NSError* error = nil;
        NSMutableDictionary* json = nil;
        
        NSString* dataString = [[NSString alloc] initWithData:_connectionData encoding:NSUTF8StringEncoding];
        NSLog(@"%@", dataString);
        
        if(nil != _connectionData)
        {
            json = [NSJSONSerialization JSONObjectWithData:_connectionData options:NSJSONReadingMutableContainers error:&amp;error];
        }
        
        if (error || !json)
        {
            NSLog(@"Could not parse loaded json with error:%@", error);
        }
        
        NSLog(@"%@", json);
        _connectionData = nil;
    }
    
    [pool drain];
    return 0;
}
</code></pre></div><div class="tab-pane" id="PHP_getmymanagerobject"><pre><code class="php">&lt;?php
　
// This sample uses the pecl_http package. (for more information: http://pecl.php.net/package/pecl_http)
require_once 'HTTP/Request2.php';
$headers = array(
);
　
$query_params = array(
	// Specify values for the following required parameters
	'api-version' =&gt; '1.6',
);
　
$request = new Http_Request2('https://graph.windows.net/me/manager');
$request-&gt;setMethod(HTTP_Request2::METHOD_GET);
$request-&gt;setHeader($headers);
　
// OAuth2 is required to access this API. For more information visit:
// https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
$url = $request-&gt;getUrl();
$url-&gt;setQueryVariables($query_params);
　
try
{
	$response = $request-&gt;send();
	
	echo $response-&gt;getBody();
}
catch (HttpException $ex)
{
	echo $ex;
}
　
?&gt;</code></pre></div><div class="tab-pane" id="PYTHON_getmymanagerobject"><pre><code class="python">
########### Python 2.7 #############
import httplib, urllib, base64
　
# OAuth2 is required to access this API. For more information visit: https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
headers = {
}
　
params = urllib.urlencode({
	# Specify values for the following required parameters
	'api-version': '1.6',
})
　
try:
	conn = httplib.HTTPSConnection('graph.windows.net')
	# Specify values for path parameters (shown as {...}) and request body if needed
	conn.request("GET", "/me/manager?%s" % params, "", headers)
	response = conn.getresponse()
	data = response.read()
	print(data)
	conn.close()
except Exception as e:
	print("[Errno {0}] {1}".format(e.errno, e.strerror))
　
####################################
　
########### Python 3.2 #############
import http.client, urllib.request, urllib.parse, urllib.error, base64
　
# OAuth2 is required to access this API. For more information visit: https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
headers = {
}
　
params = urllib.parse.urlencode({
	# Specify values for the following required parameters
	'api-version': '1.6',
})
　
try:
	conn = http.client.HTTPSConnection('graph.windows.net')
	# Specify values for path parameters (shown as {...}) and request body if needed
	conn.request("GET", "/me/manager?%s" % params, "", headers)
	response = conn.getresponse()
	data = response.read()
	print(data)
	conn.close()
except Exception as e:
	print("[Errno {0}] {1}".format(e.errno, e.strerror))
　
####################################</code></pre></div><div class="tab-pane" id="RUBY_getmymanagerobject"><pre><code class="ruby">require 'net/http'
　
uri = URI('https://graph.windows.net/me/manager')
　
uri.query = URI.encode_www_form({
	# Specify values for the following required parameters
	'api-version' =&gt; '1.6',
})
　
request = Net::HTTP::Get.new(uri.request_uri)
　
# OAuth2 is required to access this API. For more information visit: https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
　
　
response = Net::HTTP.start(uri.host, uri.port, :use_ssl =&gt; uri.scheme == 'https') do |http|
    http.request(request)
end
　
puts response.body</code></pre></div></div></div></section><hr /><h3 id="GetMyManagerLink">Get the signed-in user's manager (link) </h3><p>Gets a link to the signed-in user's manager from the <strong>manager</strong> navigation property.</p><p>On success, returns a link to the <a href="entity-and-complex-type-reference#user-entity">User</a> or <a href="entity-and-complex-type-reference#contact-entity">Contact</a> assigned as the user's manager; otherwise, the response body contains error details. For more information about errors, see <a href="../howto/azure-ad-graph-api-error-codes-and-error-handling">Error Codes and Error Handling</a>.</p><p>Returns <strong>404 Not Found</strong> if the user does not have a manager assigned.</p><section data-operation="get my manager link" class="operationDocs sampleRequestAndResponseBlock"><h4>Request</h4><pre><code class="request no-highlight"><span class="label label-success">GET</span><span class="url"> https://graph.windows.net/me/$links/manager[?api-version]</span></code></pre><div class="tryItArea"><div class="apiDetails"><input type="hidden" class="isInteractive" value="true" /><input type="hidden" class="methodType" value="GET" /><input type="hidden" class="urlToSend" value="https://graph.windows.net/me/$links/manager[?api-version]" /><h4>Parameters</h4><table class="table table-condensed"><thead><tr><th>Parameter</th><th>Type</th><th class="default">Value</th><th>Notes</th></tr></thead><tbody><tr><td colspan="4"><i>Query</i></td></tr><tr><td>api-version</td><td>string</td><td class="default"><input data-param="api-version" data-isqueryparam="true" value="1.6" /></td><td>Specifies the version of the Graph API to target. Beginning with version 1.5, the api-version string is represented in major.minor format. Prior releases were represented as date strings: '2013-11-08' and '2013-04-05'. Required.</td></tr></tbody></table></div></div><div class="requestToUpdate"><h4>Requested URL</h4><pre><code class="request no-highlight"><span class="label label-success">GET</span><span class="url"> https://graph.windows.net/me/$links/manager[?api-version]</span></code></pre></div><div class="responseList"><h4>Response</h4><div class="codeexample response"><div class="statusCode">
                        Status Code:<span class="status">200</span></div><div class="contentType"><span>Content-Type:</span><ul role="tablist"><li class="active" data-interactive="true">
application/json
                                </li></ul></div><div class="tab-content"><div class="tab-pane active" id="get_my_manager_link0" data-interactive="true"><div class="tabbedCodeSnippets"><ul class="nav nav-tabs" role="tablist"><li class="active"><a role="tabpanel" data-toggle="tab" href="#body_get_my_manager_link0">Body</a></li><li class="responseHeader" style="display:none"><a role="tabpanel" data-toggle="tab" href="#headers_get_my_manager_link0">Headers</a></li></ul><div class="tab-content"><div class="tab-pane active" id="body_get_my_manager_link0"><pre><code class="lang-js">{
  "odata.metadata": "https://graph.windows.net/myorganization/$metadata#directoryObjects/$links/manager",
  "url": "https://graph.windows.net/myorganization/directoryObjects/fabeb27a-0481-4a80-b43e-a5c02c125874/Microsoft.WindowsAzure.ActiveDirectory.User"
}</code></pre></div><div class="tab-pane" id="headers_get_my_manager_link0"><pre><code class="lang-js http"></code></pre></div></div></div></div></div></div><h4>Response List</h4><table class="responseTable"><thead><tr><th>Status Code</th><th>Description</th></tr></thead><tbody><tr><td>200</td><td>OK. Indicates success. A link to the signed-in user's manager is returned.</td></tr><tr><td>404</td><td>Not Found. The requested resource was not found. This could be due to a bad domain, a bad user ID, or can occur if the manager property is not currently set for the specified user.</td></tr></tbody></table></div><div class="tabbedCodeSnippets"><h4>Code Samples</h4><ul class="nav nav-tabs" role="tablist"><li class="active"><a role="tab" data-toggle="tab" href="#CSharp_getmymanagerlink">C#</a></li><li class=""><a role="tab" data-toggle="tab" href="#CURL_getmymanagerlink">Curl</a></li><li class=""><a role="tab" data-toggle="tab" href="#Java_getmymanagerlink">Java</a></li><li class=""><a role="tab" data-toggle="tab" href="#JS_getmymanagerlink">JavaScript</a></li><li class=""><a role="tab" data-toggle="tab" href="#ObjC_getmymanagerlink">ObjC</a></li><li class=""><a role="tab" data-toggle="tab" href="#PHP_getmymanagerlink">PHP</a></li><li class=""><a role="tab" data-toggle="tab" href="#PYTHON_getmymanagerlink">Python</a></li><li class=""><a role="tab" data-toggle="tab" href="#RUBY_getmymanagerlink">Ruby</a></li></ul><div class="tab-content"><div class="tab-pane active" id="CSharp_getmymanagerlink"><pre><code class="c#">
using System;
using System.Net.Http.Headers;
using System.Text;
using System.Net.Http;
using System.Web;
　
namespace CSHttpClientSample
{
    static class Program
    {
	    static void Main()
        {
            MakeRequest();
　
            Console.WriteLine("Hit ENTER to exit...");
            Console.ReadLine();
        }
　
        static async void MakeRequest()
        {
            var client = new HttpClient();
            var queryString = HttpUtility.ParseQueryString(string.Empty);
　
            /* OAuth2 is required to access this API. For more information visit:
               https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks */
　
　
　
			// Specify values for optional parameters, as needed
			// queryString["api-version"] = "1.6";
            // Specify values for path parameters (shown as {...})
            var uri = "https://graph.windows.net/me/$links/manager?" + queryString;
　
　
            var response = await client.GetAsync(uri);
　
            if (response.Content != null)
            {
                var responseString = await response.Content.ReadAsStringAsync();
                Console.WriteLine(responseString);
            }
        }
    }
}
</code></pre></div><div class="tab-pane" id="CURL_getmymanagerlink"><pre><code class="curl">@ECHO OFF
　
REM OAuth2 is required to access this API. For more information visit: https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
REM Specify values for path parameters (shown as {...}), values for query parameters
curl -v -X GET "https://graph.windows.net/me/$links/manager?api-version=1.6&amp;amp;"^
　
</code></pre></div><div class="tab-pane" id="Java_getmymanagerlink"><pre><code class="java">// This sample uses the Apache HTTP client from HTTP Components (http://hc.apache.org/httpcomponents-client-ga/)
import java.net.URI;
　
import org.apache.http.HttpEntity;
import org.apache.http.HttpResponse;
import org.apache.http.client.HttpClient;
import org.apache.http.client.methods.HttpGet;
import org.apache.http.client.utils.URIBuilder;
import org.apache.http.impl.client.HttpClients;
import org.apache.http.util.EntityUtils;
　
public class JavaSample {
　
  public static void main(String[] args) {
	HttpClient httpclient = HttpClients.createDefault();
　
	try
	{
		// OAuth2 is required to access this API. For more information visit:
		// https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
		// Specify values for path parameters (shown as {...})
		URIBuilder builder = new URIBuilder("https://graph.windows.net/me/$links/manager");
		// Specify values for optional parameters, as needed
		// builder.setParameter("api-version", "1.6");
		URI uri = builder.build();
		HttpGet request = new HttpGet(uri);
		HttpResponse response = httpclient.execute(request);
		HttpEntity entity = response.getEntity();
		if (entity != null) {
			System.out.println(EntityUtils.toString(entity));
		}
	}
	catch (Exception e)
	{
		System.out.println(e.getMessage());
	}
  }
}</code></pre></div><div class="tab-pane" id="JS_getmymanagerlink"><pre><code class="javascript">
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
&lt;title&gt;JSSample&lt;/title&gt;
&lt;script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js"&gt;&lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;script type="text/javascript"&gt;
	$(function() {
		// OAuth2 is required to access this API. For more information visit:
		// https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
		var params = {
			// Specify values for optional parameters, as needed
			// api-version: "1.6",
		};
		
		$.ajax({
			// Specify values for path parameters (shown as {...})
			url: 'https://graph.windows.net/me/$links/manager?' + $.param(params),
			type: 'GET',
		})
		.done(function(data) {
			alert("success");
		})
		.fail(function() {
			alert("error");
		});
	});
&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
</code></pre></div><div class="tab-pane" id="ObjC_getmymanagerlink"><pre><code class="objc">
#import &lt;Foundation/Foundation.h&gt;
　
int main(int argc, const char * argv[])
{
    NSAutoreleasePool * pool = [[NSAutoreleasePool alloc] init];
    
	// OAuth2 is required to access this API. For more information visit:
	// https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
	// Specify values for path parameters (shown as {...})
    NSString* path = @"https://graph.windows.net/me/$links/manager";
    NSArray* array = @[
                         @"entities=true",
                      ];
    
    NSString* string = [array componentsJoinedByString:@"&amp;"];
    path = [path stringByAppendingFormat:@"?%@", string];
    NSLog(@"%@", path);
　
    NSMutableURLRequest* _request = [NSMutableURLRequest requestWithURL:[NSURL URLWithString:path]];
    [_request setHTTPMethod:@"GET"];
    
    NSURLResponse *response = nil;
    NSError *error = nil;
    NSData* _connectionData = [NSURLConnection sendSynchronousRequest:_request returningResponse:&amp;response error:&amp;error];
    if(nil != error)
    {
        NSLog(@"Error: %@", error);
    }
    else
    {
        NSError* error = nil;
        NSMutableDictionary* json = nil;
        
        NSString* dataString = [[NSString alloc] initWithData:_connectionData encoding:NSUTF8StringEncoding];
        NSLog(@"%@", dataString);
        
        if(nil != _connectionData)
        {
            json = [NSJSONSerialization JSONObjectWithData:_connectionData options:NSJSONReadingMutableContainers error:&amp;error];
        }
        
        if (error || !json)
        {
            NSLog(@"Could not parse loaded json with error:%@", error);
        }
        
        NSLog(@"%@", json);
        _connectionData = nil;
    }
    
    [pool drain];
    return 0;
}
</code></pre></div><div class="tab-pane" id="PHP_getmymanagerlink"><pre><code class="php">&lt;?php
　
// This sample uses the pecl_http package. (for more information: http://pecl.php.net/package/pecl_http)
require_once 'HTTP/Request2.php';
$headers = array(
);
　
$query_params = array(
	// Specify values for optional parameters, as needed
	//'api-version' =&gt; '1.6',
);
　
$request = new Http_Request2('https://graph.windows.net/me/$links/manager');
$request-&gt;setMethod(HTTP_Request2::METHOD_GET);
$request-&gt;setHeader($headers);
　
// OAuth2 is required to access this API. For more information visit:
// https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
$url = $request-&gt;getUrl();
$url-&gt;setQueryVariables($query_params);
　
try
{
	$response = $request-&gt;send();
	
	echo $response-&gt;getBody();
}
catch (HttpException $ex)
{
	echo $ex;
}
　
?&gt;</code></pre></div><div class="tab-pane" id="PYTHON_getmymanagerlink"><pre><code class="python">
########### Python 2.7 #############
import httplib, urllib, base64
　
# OAuth2 is required to access this API. For more information visit: https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
headers = {
}
　
params = urllib.urlencode({
	# Specify values for optional parameters, as needed
	#'api-version': '1.6',
})
　
try:
	conn = httplib.HTTPSConnection('graph.windows.net')
	# Specify values for path parameters (shown as {...}) and request body if needed
	conn.request("GET", "/me/$links/manager?%s" % params, "", headers)
	response = conn.getresponse()
	data = response.read()
	print(data)
	conn.close()
except Exception as e:
	print("[Errno {0}] {1}".format(e.errno, e.strerror))
　
####################################
　
########### Python 3.2 #############
import http.client, urllib.request, urllib.parse, urllib.error, base64
　
# OAuth2 is required to access this API. For more information visit: https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
headers = {
}
　
params = urllib.parse.urlencode({
	# Specify values for optional parameters, as needed
	#'api-version': '1.6',
})
　
try:
	conn = http.client.HTTPSConnection('graph.windows.net')
	# Specify values for path parameters (shown as {...}) and request body if needed
	conn.request("GET", "/me/$links/manager?%s" % params, "", headers)
	response = conn.getresponse()
	data = response.read()
	print(data)
	conn.close()
except Exception as e:
	print("[Errno {0}] {1}".format(e.errno, e.strerror))
　
####################################</code></pre></div><div class="tab-pane" id="RUBY_getmymanagerlink"><pre><code class="ruby">require 'net/http'
　
uri = URI('https://graph.windows.net/me/$links/manager')
　
uri.query = URI.encode_www_form({
	# Specify values for optional parameters, as needed
	# 'api-version' =&gt; '1.6',
})
　
request = Net::HTTP::Get.new(uri.request_uri)
　
# OAuth2 is required to access this API. For more information visit: https://int.msdn.microsoft.com/en-us/office/office365/howto/common-app-authentication-tasks
　
　
　
response = Net::HTTP.start(uri.host, uri.port, :use_ssl =&gt; uri.scheme == 'https') do |http|
    http.request(request)
end
　
puts response.body</code></pre></div></div></div></section><hr /><h3 id="SetMyManager">Update the signed-in user's manager </h3><p>Assigns the signed-in user's manager through the <strong>manager</strong> property. Either a user or a contact may be assigned. The request body contains a link to the <a href="entity-and-complex-type-reference#user-entity">User</a> or <a href="entity-and-complex-type-reference#contact-entity">Contact</a> to assign. </p><p>On success, no response body is returned; otherwise, the response body contains error details. For more information about errors, see <a href="../howto/azure-ad-graph-api-error-codes-and-error-handling">Error Codes and Error Handling</a>.</p><section data-operation="set my manager" class="operationDocs sampleRequestAndResponseBlock"><h4>Request</h4><pre><code class="request no-highlight"><span class="label label-warning">PUT</span><span class="url"> https://graph.windows.net/me/$links/manager?api-version</span></code></pre><div class="tryItArea"><div class="apiDetails"><input type="hidden" class="methodType" value="PUT" /><input type="hidden" class="urlToSend" value="https://graph.windows.net/me/$links/manager?api-version" /><h4>Parameters</h4><table class="table table-condensed"><thead><tr><th>Parameter</th><th>Type</th><th class="default">Value</th><th>Notes</th></tr></thead><tbody><tr><td colspan="4"><i>Query</i></td></tr><tr><td>api-version</td><td>string</td><td class="default"><input data-param="api-version" data-isqueryparam="true" value="1.6" /></td><td>Specifies the version of the Graph API to target. Beginning with version 1.5, the api-version string is represented in major.minor format. Prior releases were represented as date strings: '2013-11-08' and '2013-04-05'. Required.</td></tr><tr><td colspan="4" class="bodyParameterHeading"><i>Body</i></td></tr><tr><td colspan="4">
                                
　
Content-Type: application/json
<pre><code class="lang-js">{
  "url": "https://graph.windows.net/contoso.onmicrosoft.com/directoryObjects/fabeb27a-0481-4a80-b43e-a5c02c125874"
}</code></pre></td></tr></tbody></table></div></div><div class="requestToUpdate"><h4>Requested URL</h4><pre><code class="request no-highlight"><span class="label label-warning">PUT</span><span class="url"> https://graph.windows.net/me/$links/manager?api-version</span></code></pre></div><div class="responseList"><h4>Response</h4><div class="codeexample response"><div class="statusCode">
                        Status Code:<span class="status">204</span></div><div class="contentType"><span>Content-Type:</span><ul role="tablist"><li class="active" data-interactive="true">
application/json
                                </li></ul></div><div class="tab-content"><div class="tab-pane active" id="set_my_manager0" data-interactive="true"><div class="tabbedCodeSnippets"><ul class="nav nav-tabs" role="tablist"><li class="active"><a role="tabpanel" data-toggle="tab" href="#body_set_my_manager0">Body</a></li><li class="responseHeader" style="display:none"><a role="tabpanel" data-toggle="tab" href="#headers_set_my_manager0">Headers</a></li></ul><div class="tab-content"><div class="tab-pane active" id="body_set_my_manager0"><pre><code class="lang-js">none</code></pre></div><div class="tab-pane" id="headers_set_my_manager0"><pre><code class="lang-js http"></code></pre></div></div></div></div></div></div><h4>Response List</h4><table class="responseTable"><thead><tr><th>Status Code</th><th>Description</th></tr></thead><tbody><tr><td>204</td><td>No Content. Indicates success. No response body is returned.</td></tr><tr><td>404</td><td>Not Found. The requested resource was not found. For exmaple, this could be due to a bad domain.</td></tr></tbody></table></div></section><hr /><h3 id="other-navigation-properties">Other navigation properties</h3><p>By using the same patterns shown above, you can target other navigation properties exposed by users. Some properties are read-only and others may be modified. For more information about user navigation properties, see the documentation for <a href="entity-and-complex-type-reference#user-entity">User</a>. </p><hr /><h2 id="Functions">Functions and actions on the signed-in user </h2><p>You can call any of the following functions or actions on the signed-in user by using the <code>me</code> alias.</p><h3 id="assign-and-remove-licenses">Assign and remove licenses</h3><p>You can call the <a href="functions-and-actions#assignLicense">assignLicense</a> action to assign or remove licenses for a user and to enable or disable specific plans for the user.</p><h3 id="change-password-of-the-signed-in-user">Change password of the signed-in user</h3><p>You can call the <a href="functions-and-actions#changePassword">changePassword</a> action to enable the signed-in user to change their password.</p><h3 id="check-membership-in-a-list-of-groups-transitive">Check membership in a list of groups (transitive)</h3><p>You can call the <a href="functions-and-actions#checkMemberGroups">checkMemberGroups</a> function to check for membership in a list of groups. The check is transitive.</p><h3 id="get-all-group-memberships-transitive">Get all group memberships (transitive)</h3><p>You can call the <a href="functions-and-actions#getMemberGroups">getMemberGroups</a> function to return all the groups that the user is a member of. The check is transitive, unlike reading the <strong>memberOf</strong> navigation property, which returns only the groups that the user is a direct member of.</p><h3 id="get-all-group-and-directory-role-memberships-transitive">Get all group and directory role memberships (transitive)</h3><p>You can call the <a href="functions-and-actions#getMemberObjects">getMemberObjects</a> function to return all of the groups and directory roles that the user is a member of. The check is transitive, unlike reading the <strong>memberOf</strong> navigation property, which returns only the groups that the user is a direct member of.</p><hr /><h2 id="additional-resources">Additional Resources</h2><ul><li>Learn more about Graph API supported features, capabilities, and preview features in <a href="../howto/azure-ad-graph-api-operations-overview">Graph API concepts</a></li></ul></div><div id="right-nav-wrapper" class="col-md-3"><div id="right-nav-area" class="bs-sidebar affix"><ul id="task-nav-list" class="nav bs-sidenav" ms.cmpgrp="indoc toc"><li class="nav-header">IN THIS ARTICLE</li><li><a class="" href="#Signed-in_User">Performing REST operations on the signed-in user </a></li><li><a class="" href="#BasicOperations">Basic operations on the signed-in user </a></li><li><a class="sub-task" href="#GetMe">Get the signed-in user </a></li><li><a class="sub-task" href="#UpdateMe">Update the signed-in user </a></li><li><a class="" href="#NavigationOps">Operations on navigation properties </a></li><li><a class="sub-task" href="#GetMyManagerObject">Get the signed-in user's manager (object) </a></li><li><a class="sub-task" href="#GetMyManagerLink">Get the signed-in user's manager (link) </a></li><li><a class="sub-task" href="#SetMyManager">Update the signed-in user's manager </a></li><li><a class="sub-task" href="#other-navigation-properties">Other navigation properties</a></li><li><a class="" href="#Functions">Functions and actions on the signed-in user </a></li><li><a class="sub-task" href="#assign-and-remove-licenses">Assign and remove licenses</a></li><li><a class="sub-task" href="#change-password-of-the-signed-in-user">Change password of the signed-in user</a></li><li><a class="sub-task" href="#check-membership-in-a-list-of-groups-transitive">Check membership in a list of groups (transitive)</a></li><li><a class="sub-task" href="#get-all-group-memberships-transitive">Get all group memberships (transitive)</a></li><li><a class="sub-task" href="#get-all-group-and-directory-role-memberships-transitive">Get all group and directory role memberships (transitive)</a></li><li><a class="" href="#additional-resources">Additional Resources</a></li></ul></div></div></div>
        
　
<input type="hidden" id="proxyUrl" value="https://apiexproxy.azurewebsites.net/svc" />
<input type="hidden" id="playgroundUrl" value="https://apisandbox.msdn.microsoft.com/" />
<input type="hidden" id="ajaxTimeout" value="10000" />
<input type="hidden" id="supportedLanguagesForPlayground" value="javascript;c#" />
<input type="hidden" id="authorizationHeader" value="Bearer {token:{resourceName}}" />
　
　
　
　
            <div id="commentArea"><div id="commentContainer"></div></div>
            
    </div>
    <div id="rightColumn" class="right" ms.cmpgrp="right nav">
            <div id="right-nav-wrapper">
        <div id="right-nav-area" class="bs-sidebar affix">
            <div id="navigationButtons">
                <a id="isdSmile" title="Feedback" href="#">
                    <ins class="smile"></ins>
                    Feedback
                </a>
　
                    <a id="isdContribute" target="_blank" title="Contribute" href="https://github.com/Microsoft/aad-graph-api-docs-pr/blob/master/docs/api/signed-in-user-operations.md">
                        <ins class="contribute"></ins>
                        Contribute
                    </a>
　
                <a id="isdShare" title="Share" href="#" role="button" aria-expanded="false">
                    <ins class="share"></ins>
                    Share
                </a>
                <div id="socials" style="display: none">
                    <a class="isdFacebook" title="Share on Facebook" href="#" data-sitename="Facebook" aria-label="Share on Facebook">
                        <ins class=" facebook"></ins>
                    </a>
                    <a class="isdTwitter" title="Share on Twitter" href="#" data-sitename="Twitter" aria-label="Share on Twitter">
                        <ins class="twitter"></ins>
                    </a>
                    <a class="isdGooglePlus" title="Share on Google+" href="#" data-sitename="Google+" aria-label="Share on Google+">
                        <ins class="googlePlus"></ins>
                    </a>
                </div>
　
            </div>
        </div>
    </div>
　
    </div>
</div>
　
　
　
　
　
　
　
        </div>
　
          
            
            <div id="openFeedbackContainer" style="z-index:220;" ms.pgarea="body" ms.cmpgrp="feedbackform"></div>
            
　
        
    
　
    
    <link type="text/css" rel="stylesheet" />
    
        
    <div id="ux-footer" class="" style="" dir="ltr" ms.pgarea="footer">
　
　
    <div id="standardRatingBefore" class="clear stdr-container-before"></div>
    <div id="standardRating" class="stdr-container" ms.pgarea="body">
        <div class="stdr-close"></div>
        <div class="stdr-vote stdr-content">
            <div class="stdr-content">
                <span class="stdr-votetitle">Is this page helpful?</span>
                <button class="stdr-yes" aria-label="Yes, this page was helpful">Yes</button>
                <button class="stdr-no" aria-label="No, this page was not helpful">No</button>
                <input id="s_ratingValue" type="hidden" value="" />
            </div>
        </div>
        <div class="stdr-feedback" style="display: none">
            <div class="stdr-form">
                <div class="stdr-fieldtitle">Additional feedback?</div>
                <textarea class="stdr-detail" rows="6" maxlength="1500"></textarea>
                <div>
                    <span class="stdr-count"><span class="stdr-charcnt">1500</span> characters remaining</span>
                    <div class="stdr-buttons">
                        <button class="stdr-provide" aria-label="Submit my additional feedback">Submit</button>
                        <button class="stdr-skip" aria-label="Skip additional feedback">Skip this</button>
                    </div>
                </div>
                <div class="clear"></div>
            </div>
        </div>
        <div class="stdr-thanks" style="display: none">
            <div class="stdr-content">
                <span class="stdr-thankyou">Thank you!</span>
                <span class="stdr-appreciate">We appreciate your feedback.</span>
            </div>
        </div>
　
        
        <div id="contentFeedbackQAContainer" style="display: none;"></div>
    </div>
    <div id="standardRatingPlaceholder" style="display: none"></div>
    
　
        <footer class="top" role="navigation" aria-label="footer">
            <div data-fragmentName="LeftLinks" id="Fragment_LeftLinks" xmlns="http://www.w3.org/1999/xhtml">
  
  <div class="linkList">
    <h4 class="linkListTitle">Dev centers</h4>
    <ul class="links">
      <li>
        <a href="https://developer.microsoft.com/en-us/windows" id="LeftLinks_2148_1" class="windowsBlue" xmlns="http://www.w3.org/1999/xhtml">Windows</a>
      </li>
      <li>
        <a href="https://dev.office.com/" id="LeftLinks_2148_3" class="office" xmlns="http://www.w3.org/1999/xhtml">Office</a>
      </li>
      <li>
        <a href="https://www.visualstudio.com/" id="LeftLinks_2148_4" class="visualStudio" xmlns="http://www.w3.org/1999/xhtml">Visual Studio</a>
      </li>
      <li>
        <a href="https://docs.microsoft.com/en-us/azure/" target="_blank" id="LeftLinks_2148_12" xmlns="http://www.w3.org/1999/xhtml">Microsoft Azure</a>
      </li>
      <li>
        <a href="https://int.msdn.microsoft.com/developer-centers-msdn" id="LeftLinks_2148_5" xmlns="http://www.w3.org/1999/xhtml">More...</a>
      </li>
    </ul>
  </div>
</div>
            <div id="rightLinks">
                <div data-fragmentName="CenterLinks1" id="Fragment_CenterLinks1" xmlns="http://www.w3.org/1999/xhtml">
  
  <div class="linkList">
    <h4 class="linkListTitle">Learning resources</h4>
    <ul class="links">
      <li>
        <a href="https://mva.microsoft.com/" id="CenterLinks1_2151_4" xmlns="http://www.w3.org/1999/xhtml">Microsoft Virtual Academy</a>
      </li>
      <li>
        <a href="https://channel9.msdn.com/" id="CenterLinks1_2151_5" xmlns="http://www.w3.org/1999/xhtml">Channel 9</a>
      </li>
      <li>
        <a href="https://int.msdn.microsoft.com/magazine/" id="CenterLinks1_2151_7" xmlns="http://www.w3.org/1999/xhtml">MSDN Magazine</a>
      </li>
    </ul>
  </div>
</div>
                <div data-fragmentName="CenterLinks2" id="Fragment_CenterLinks2" xmlns="http://www.w3.org/1999/xhtml">
  
  <div class="linkList">
    <h4 class="linkListTitle">Community</h4>
    <ul class="links">
      <li>
        <a href="https://social.msdn.microsoft.com/forums/en-us/home" id="CenterLinks2_2151_8" xmlns="http://www.w3.org/1999/xhtml">Forums</a>
      </li>
      <li>
        <a href="https://blogs.msdn.microsoft.com/developer-tools/" id="CenterLinks2_2151_9" xmlns="http://www.w3.org/1999/xhtml">Blogs</a>
      </li>
      <li>
        <a href="https://www.codeplex.com/" id="CenterLinks2_2151_10" xmlns="http://www.w3.org/1999/xhtml">Codeplex</a>
      </li>
    </ul>
  </div>
</div>
                <div data-fragmentName="CenterLinks3" id="Fragment_CenterLinks3" xmlns="http://www.w3.org/1999/xhtml">
  
  <div class="linkList">
    <h4 class="linkListTitle">Support</h4>
    <ul class="links">
      <li>
        <a href="https://int.msdn.microsoft.com/hh361695" id="CenterLinks3_2151_11" xmlns="http://www.w3.org/1999/xhtml">Self support</a>
      </li>
    </ul>
  </div>
</div>
                <div data-fragmentName="CenterLinks4" id="Fragment_CenterLinks4" xmlns="http://www.w3.org/1999/xhtml">
  
  <div class="linkList">
    <h4 class="linkListTitle">Programs</h4>
    <ul class="links">
      <li>
        <a href="https://bizspark.microsoft.com/Startups/Index" id="CenterLinks4_2151_13" xmlns="http://www.w3.org/1999/xhtml">BizSpark (for startups)</a>
      </li>
      <li>
        <a href="https://imagine.microsoft.com/en-us" id="CenterLinks4_2151_22" xmlns="http://www.w3.org/1999/xhtml">Microsoft Imagine (for students)</a>
      </li>
    </ul>
  </div>
</div>
            </div>
        </footer>
　
        <footer class="bottom" role="contentinfo">
            <span class="localeContainer">
                
    <form class="selectLocale" id="selectLocaleForm" action="https://int.msdn.microsoft.com/en-us/selectlocale-dmc">
        <input type="hidden" name="fromPage" value="https%3a%2f%2fint.msdn.microsoft.com%2fen-us%2fLibrary%2fAzure%2fAd%2fGraph%2fapi%2fsigned-in-user-operations" />
        <a href="#" onclick="$('#selectLocaleForm').submit();return false;" title="Change your language">United States (English)</a>
    </form>
　
　
            </span>
　
            <div data-fragmentName="BottomLinks" id="Fragment_BottomLinks" xmlns="http://www.w3.org/1999/xhtml">
  
  <div class="linkList">
    <ul class="links horizontal">
      <li>
        <a href="https://int.msdn.microsoft.com/en-us/flashnewsletter" id="BottomLinks_2148_7" xmlns="http://www.w3.org/1999/xhtml">Newsletter</a>
      </li>
      <li>
        <a href="https://int.msdn.microsoft.com/en-us/dn529288" id="BottomLinks_2148_8" xmlns="http://www.w3.org/1999/xhtml">Privacy &amp; cookies</a>
      </li>
      <li>
        <a href="https://int.msdn.microsoft.com/en-us/cc300389" id="BottomLinks_2148_9" xmlns="http://www.w3.org/1999/xhtml">Terms of use</a>
      </li>
      <li>
        <a href="https://www.microsoft.com/en-us/legal/intellectualproperty/Trademarks/" id="BottomLinks_2148_10" xmlns="http://www.w3.org/1999/xhtml">Trademarks</a>
      </li>
    </ul>
  </div>
</div>
            <span class="logoLegal">
                <span class="logoSpan clip67x13" role="img" tabindex="0" aria-label="microsoft logo">
                    <img alt="logo" class="logo" src="https://i1.int.msdn.microsoft.com/Areas/Centers/Themes/StandardDevCenter/Content/HeaderFooterSprite.png?v=636239072718341861" />
                </span>
                <span class="copyright">© 2017 Microsoft</span>
            </span>
        </footer>
    </div>
    
　
　
　
        <div class="footerPrintView">
            <div class="footerCopyrightPrintView">© 2017 Microsoft</div>
        </div>
　
        
    
　
　
<![CDATA[ WebTrends view model not available or IncludeLegacyWebTrendsScriptInGlobal feature flag is off]]>
　
　
    </div>
　
    
    
　
    
    
　
<![CDATA[ Third party scripts and code linked to or referenced from this website are licensed to you by the parties that own such code, not by Microsoft.  See ASP.NET Ajax CDN Terms of Use – http://www.asp.net/ajaxlibrary/CDN.ashx. ]]>
    
<script type="text/javascript" class="mtps-injected">
/*<![CDATA[*/
(function(window,document){"use strict";function preload(scripts){for(var result=[],script,e,i=0;i<scripts.length;i++)script=scripts[i],script.hasOwnProperty("url")&&(e=document.createElement("script"),e.src=script.url,script.throwaway=e),result.push(script);return result}function inject(scripts,index){var script,elem;if(index>=scripts.length){delete mtps.injectScripts;return}script=scripts[index];elem=document.createElement("script");elem.className="mtps-injected";elem.async=!1;var isLoaded=!1,timeoutId=0,injectNextFnName="",injectNext=elem.onerror=function(){isLoaded||(isLoaded=!0,inject(scripts,index+1),window.clearTimeout(timeoutId),elem.onload=elem.onerror=elem.onreadystatechange=null,injectNextFnName&&delete mtps[injectNextFnName],elem.removeEventListener&&elem.removeEventListener("load",injectNext,!1))};elem.addEventListener?elem.addEventListener("load",injectNext,!1):elem.readyState==="uninitialized"?elem.onreadystatechange=function(){(this.readyState==="loaded"||this.readyState==="complete")&&injectNext()}:elem.onload=injectNext;script.hasOwnProperty("url")?(timeoutId=window.setTimeout(injectNext,12e4),elem.src=script.url):(injectNextFnName="_injectNextScript_"+index,mtps[injectNextFnName]=injectNext,timeoutId=window.setTimeout(injectNext,2e3),elem.text="try {\n"+script.txt+"\n} finally { MTPS."+injectNextFnName+" && MTPS."+injectNextFnName+"(); }");parent.appendChild(elem)}var mtps=window.MTPS||(window.MTPS={}),parent=document.getElementsByTagName("head")[0];mtps.injectScripts=function(scripts){inject(preload(scripts),0)}})(window,document);
MTPS.injectScripts([
	{ txt: "/**/\r\n(window.MTPS || (window.MTPS = {})).cdnDomains || (window.MTPS.cdnDomains = { \r\n\t\"image\": \"https://i1.int.msdn.microsoft.com\", \r\n\t\"js\": \"https://i2.int.msdn.microsoft.com\", \r\n\t\"css\": \"https://i3.int.msdn.microsoft.com\", \r\n\t\"xap\": \"https://i4.int.msdn.microsoft.com\", \r\n\t\"ttf\": \"https://i3.int.msdn.microsoft.com\"\r\n});\r\n/**/" },
	{ url: "https://open-rating.azureedge.net/open-rating.entry.min.js" },
	{ txt: "//\n\n        window.appInsightsId = \u00275eb1b2eb-c47a-497a-a7ac-a1c230b2882f\u0027;\n        //" },
	{ url: "https://i2.int.msdn.microsoft.com/Combined.js?resources=0:OpenPublishingResponsiveTable,0:OpenPublishingResponsiveVideo,1:Layout,2:Header,2:Footer,3:ResponsiveSupport,0:AppInsightsPerf,0:Telemetry,0:InteractionTracker,0:ABTestControl,4:WEDCS;/Areas/Epx/Content/Scripts:0,/Areas/Epx/Themes/Base/Content:1,/Areas/Centers/Themes/StandardDevCenter/Content:2,/Areas/Library/Content:3,/Areas/Library/Themes/Base/Content:4\u0026amp;hashKey=D567CF9FC92F5D3FBB0CB0CBA77D7613\u0026amp;v=154301FA4C7F6409DEAD6F5D68D7912F" },
	{ url: "https://ajax.aspnetcdn.com/ajax/bootstrap/3.3.6/bootstrap.min.js" },
	{ url: "https://i2.int.msdn.microsoft.com/Combined.js?resources=0:Utilities,0:highlight.min,0:OACodeSnippet,1:SearchBox;/Areas/Epx/Content/Scripts:0,/Areas/Epx/Themes/Base/Content:1\u0026amp;hashKey=0FB04913BC8BD6BD9728A63BC62F8C06\u0026amp;v=154301FA4C7F6409DEAD6F5D68D7912F" },
	{ url: "https://i1.qa.services.social.microsoft.com/search/Widgets/SearchBox.jss?boxid=HeaderSearchTextBox\u0026btnid=HeaderSearchButton\u0026minimumTermLength=2\u0026pgArea=header\u0026brand=Msdn\u0026loc=en-us\u0026focusOnInit=false\u0026emptyWatermark=true\u0026searchButtonTooltip=Search MSDN" },
	{ url: "https://i2.int.msdn.microsoft.com/Combined.js?resources=0:JumpRedirect,1:OpenPublishingMobileMenu,1:apiRunner;/Areas/Epx/Themes/Base/Content:0,/Areas/Epx/Content/Scripts:1\u0026amp;hashKey=21D077BA193446B105A04E76D18C918B\u0026amp;v=154301FA4C7F6409DEAD6F5D68D7912F" },
	{ txt: "//\n                var CommentElementId = \"commentContainer\";\n                //" },
	{ url: "https://i2.int.msdn.microsoft.com/Combined.js?resources=0:OpenPublishingTopic,1:API.1;/Areas/Epx/Content/Scripts:0,/Areas/Epx/Themes/Base/Content:1\u0026amp;hashKey=C69ED4BFA3169700AEE76B69B56458D1\u0026amp;v=154301FA4C7F6409DEAD6F5D68D7912F" },
	{ txt: "//\n                // Load metadata into map to speed up reading later.\n                var metadataMap = {};\n                var metadataElements = document.getElementsByTagName(\"meta\");\n                for (var i = 0; i \u003c metadataElements.length; ++i)\n                {\n                    var meta = metadataElements[i];\n                    var name = meta.getAttribute(\"name\");\n                    if (name)\n                    {\n                        metadataMap[name.toLowerCase()] = meta.getAttribute(\"content\");\n                    }\n                }\n\n                window.openFeedbackOptions =\n                {\n                    environment: \"devint\",\n                    anonUserCookieName:\"A\",\n                    documentMetaName: \"ms.documentid\",\n                    documentSnapIdMetaName: \"ms.gitcommit\",\n                    localeMetaName: \"ms.locale\",\n                    propertyBag:\n                    {\n                        \"ms.depotname\": metadataMap[\"ms.depotname\"],\n                        \"ms.contentsource\": metadataMap[\"ms.contentsource\"]\n                    }\n                };\n                //" },
	{ url: "https://i2.int.msdn.microsoft.com/Combined.js?resources=0:StandardRating,1:Breadcrumbs;/Areas/Global/Content:0,/Areas/Library/Content:1\u0026amp;hashKey=0745C0808597989A9FBBD566CA324EB1\u0026amp;v=154301FA4C7F6409DEAD6F5D68D7912F" }
]);
　
/*]]>*/
</script></body>
</html>
　
