====
Page
====

Types
=====

    +-----------------------------+----------------------------------------+
    |   Type                      |     Possible Direct Parent Type        |
    +=============================+========================================+
    | Activity List               | Any type                               |
    +-----------------------------+----------------------------------------+
    | Activity                    | Activity List                          |
    +-----------------------------+----------------------------------------+
    | Announcement List           | Any type                               |
    +-----------------------------+----------------------------------------+
    | Announcement                | Announcement List                      |
    +-----------------------------+----------------------------------------+

	* Activity List
	* Activity
	* Announcement List
	* Announcement
	* Contact Form Page
	* Contact Page
	* Directorate List
	* Directorate
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


``Body``
````````

	The page content. You can insert text, images, videos and documents.

	.. image:: static/page_content_body.jpg


``Images``
``````````

	Single or multiple images can be uploaded. Supported formats are **``.jpg``** and **``.png``**. Maximum file size is **10MB**. 

	.. image:: static/page_content_images.jpg