{
  "build": {
    "content": [
      {
        "files": [
          "**/*.md"
        ],
        "exclude": [
          "**/obj/**",
          "**/includes/**",
          "**/old-TOC.md"
        ]
      }
    ],
    "resource": [
      {
        "files": [
          "**/images/**",
          "**/*.png",
          "**/*.jpg",
          "**/*.gif",
          "**/*.bmp",
          "**/*.html",
          "**/*.css"
        ],
        "exclude": [
          "**/obj/**",
          "_themes/**"
        ]
      }
    ],
    "dest": "user-help",
    "template": "docs.html",
    "globalMetadata": {
      "layout": "Conceptual",
      "breadcrumb_path": "/mem/breadcrumb/toc.json",
      "product_feedback_displaytext": "Intune Feedback",
      "product_feedback_url": "https://microsoftintune.uservoice.com/",
      "feedback_system": "GitHub",
      "feedback_github_repo": "MicrosoftDocs/Intunedocs",      
      "contributors_to_exclude": [
        "herohua",
        "fenxu"
      ],
      "searchScope": [
        "Intune"
      ],
      "_op_documentIdPathDepotMapping": {
        "./": {
          "depot_name": "Azure.EndUser",
          "folder_relative_path_in_docset": "."
        }
      }
    },
    "markdownEngineName": "markdig"
  }
}