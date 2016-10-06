====
Page
====

Types
=====
    
    Pages are classified into types to meet different aspects. They are:

    .. note::
        Types ending with "list" are just containers for the types with the preceding word. For example, ``Activity List`` page has to be added as a parent of the subsequent ``Activity`` pages.

    +-----------------------------+--------------------------------------------+---------------------------------------------+
    |   Type                      |     Allowed Parent Type                    |      Allowed Child Type                     |
    +=============================+============================================+=============================================+
    | Activity List               | [a]_                                       | Activity                                    |
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Activity                    | Activity List                              | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Announcement List           | [a]_                                       | Annoucement                                 |
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Announcement                | Announcement List                          | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Contatc Form Page           | [a]_                                       | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Contatc Page                | [a]_                                       | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Directorate List            | [a]_                                       | Directorate                                 | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Directorate                 | Directorate List                           | [c]_ [s]_ except ``College``                | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Event List                  | [a]_                                       | Event                                       | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Event                       | Event List                                 | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Form Page                   | [a]_                                       | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | News List                   | [a]_                                       | News                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | News                        | News List                                  | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Office List                 | [a]_                                       | Office                                      | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Office                      | Office List                                | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Page                        | [a]_                                       | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Project List                | [a]_                                       | Project                                     | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Project                     | Project List                               | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Research List               | [a]_                                       | Research                                    | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Research                    | Research List                              | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Scholarship List            | [a]_                                       | Scholarship                                 | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Sccholarship                | Scholarship List                           | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Workshop List               | [a]_                                       | Workshop                                    | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Workshop                    | Workshop List                              | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Seminar List                | [a]_                                       | Seminar                                     | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Seminar                     | Seminar List                               | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Unit List                   | [a]_                                       | Unit                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Unit                        | Unit List                                  | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | College List                | [l]_                                       | College                                     | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | College                     | College List                               | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Center List                 | [s]_ excpet ``Center``                     | Center                                      | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+
    | Center                      | Center List                                | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+



    .. [a] **Any type**.
    .. [-] **None**.
    .. [c] **Common**: Activity, Announcement, Contatc Form Page, Contact Page, Event List, Form Page, News List, Page, Project List, Research List, Scholarship List, Seminar List, Workshop List.
    .. [s] **Spatial**: Office, College, Unit, Center, Directorate
    .. [l] **LOCKED**



Fields
======

Content
-------

``Title``
`````````

    The ``title`` is required (at least in English (EN)), without it the page can not be created. ``Title`` is also equired for auto-generating the ``Slug`` and the HTML ``Page title``.

    .. image:: static/page_content_title.jpg
       :target: _images/page_content_title.jpg

.. tip::
    If you don't have the English translation of your article title, just paste in the available one (Arabic or Kurdish).


----------


``Body``
````````

    The page content can have text, images, videos and documents.

    .. image:: static/page_content_body.jpg
        :target: _images/page_content_body.jpg


----------


``Images``
``````````

    Unlimited number of images can be added to the page. Supported formats are ``.jpg`` and ``.png``. Maximum file size is **10MB**. 

    .. tip::
        Images can link to pages or external web pages. Use ``Link page`` or ``External Link`` for this purpose.

    .. image:: static/page_content_images.jpg
        :target: _images/page_content_images.jpg


----------


``Related Links``
`````````````````

    You may find it useful sometimes to add some related content links for the reader. Number of links are unlimited.

    .. image:: static/page_content_relatedlinks.jpg
        :target: _images/page_content_relatedlinks.jpg


----------



Promote
-------

HomePage
````````
.. image:: static/page_promote_homepage.jpg
    :target: _images/page_promote_homepage.jpg


``Slideshow Request``
`````````````````````
    Ticking this notifies the super admin to approve the content and get displayed on the homepage slideshow.
        * **Type**: Check Box. 
        * **Default Value**: Unchecked.
    
    .. image:: static/page_promote_homepage_slideshow.jpg
        :target: _images/page_promote_homepage_slideshow.jpg

.. warning::
    Be careful. Choosing inappropriate content may cause denial.

    The first image added, to the article, is used for the slideshow. Invalid images will be rejected. Please take a look at the **image specifications policy**.


``Breaking News Request``
`````````````````````````
    Ticking this notifies the super admin to approve the content and get displayed on the homepage breaking news bar.
        * **Type**: Check Box. 
        * **Default Value**: Unchecked.

    .. image:: static/page_promote_homepage_breakingnews.jpg
        :target: _images/page_promote_homepage_breakingnews.jpg    


``HomePage Body Request``
`````````````````````````
    Ticking this notifies the super admin to approve the content and get displayed on the homepage "Top Stories" section. 
        * **Type**: Check Box. 
        * **Default Value**: Unchecked.


    .. image:: static/page_promote_homepage_body.jpg
        :target: _images/page_promote_homepage_body.jpg


Side Menu
`````````
.. image:: static/page_promote_sidemenu.jpg
    :target: _images/page_promote_sidemenu.jpg


``Sidemenu``
````````````
    Displays or hides the side menu on the page.
        * **Type**: Check Box. 
        * **Default Value**: Checked.


``Show in sidemenu``
````````````````````
    Adds the link of the page as an item in the sidemenu. 
        * **Type**: Check Box. 
        * **Default Value**: Unchecked.

``Sidemenu Order``
````````````````````
    The order of the page link among its siblings on the same menu level.  
        * **Type**: Integer.
        * **Default Value**: 0.

    .. note::
        Ordering starts from the minimum value and goes down with the increase of the value. So, zero (0) is on the top, (1) one is the next and so on.

    .. tip::
        For a more dynamic approach, put the value (0) for the first item, and (10) for the second, (20) for the third and so on. In this way you'll save some places for the new outcome items, to be inserted between, as needed. 

    .. note::
        Similar values are handled on the basis of alphabetical order.


``Sidemenu Parent``
```````````````````
    Each page has a parent. But if you want to change it in the side menu you can replace it here.  
        * **Type**: Page.
        * **Default Value**: Null.