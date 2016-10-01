====
Page
====

Types
=====

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
    | Directorate                 | Directorate List                           | [c]_                                        | 
    +-----------------------------+--------------------------------------------+---------------------------------------------+

    .. [a] Any type.

    .. [-] None.

    .. [c] **Common types**: Activity, Announcement, Contatc Form Page, Contact Page, Event List, Form Page, News List, Page, Project List, Research List, Scholarship List, Seminar List, Workshop List.


	* Event List
	* Event
	* Form Page
	* News List
	* News
	* Office List
	* Office
	* Page
	* Project List
	* Project
	* Research List
	* Research
	* Scholarship List
	* Scholarship
	* Seminar List
	* Seminar
	* Unit List
	* Unit
	* Workshop List
	* Workshop
	* College List [Academic]
	* College
	* Center List [college, unit, directoare, office]
	* Center
	* Department List (Academic)
	* Department (Academic) 
	* Department List (Administrative) [directorate, unit, office, center, college]
	* Department (Administrative)
	* Research Center List
	* Research Center
	* Research List
	* Research
	* Staff List (Administrative) [unit, directorate, office, college, department (academic), department (administrative)]
	* Member (Administrative)
	* Staff List (Academic) [department (academic), ]
	* Member (Academic)
	* Unit List
	* Unit
	* Course List [department (academic)]
	* Stage List [course list]
	* Stage [stage list]
	* Course [stage]


Fields
======

Content
-------

``Title``
`````````

	The English (EN) title is required, without it the page can not be created. ``Title`` is also equired for auto-generating ``Slug`` and HTML ``Page title``.

	.. image:: static/page_content_title.jpg

.. tip::
    If you don't have the English translation of your article title, just paste in the available one (Arabic or Kurdish).


----------


``Body``
````````

	The page content. Text, images, videos and documents can be inserted.

	.. image:: static/page_content_body.jpg


----------


``Images``
``````````

	Unlimited number of images can be added to the page. Supported formats are ``.jpg`` and ``.png``. Maximum file size is **10MB**. 

	.. image:: static/page_content_images.jpg