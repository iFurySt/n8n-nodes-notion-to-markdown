![Banner image](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

# n8n-nodes-notion-to-markdown

This is an n8n community node that allows you to convert Notion pages to Markdown format.

Notion is a powerful note-taking and knowledge management tool. This node helps you convert Notion page content to Markdown format, making it easier to migrate and share content.

[n8n](https://n8n.io/) is a [fair-code licensed](https://docs.n8n.io/reference/license/) workflow automation platform.

[Installation](#installation)  
[Operations](#operations)  
[Credentials](#credentials)  
[Compatibility](#compatibility)  
[Usage](#usage)  
[Resources](#resources)  

## Installation

To install this node in n8n:

1. Click the three dots next to your profile in the bottom left corner
2. Go to Settings -> Community nodes
3. Click "Install a community node"
4. Enter `n8n-nodes-notion-to-markdown`
5. Check the box and click Install

## Operations

* Convert Page to Markdown - Convert a Notion page to Markdown format

## Credentials

You need to provide a Notion API key to use this node. Here's how to get your API key:

1. Visit [Notion Developers](https://www.notion.so/my-integrations)
2. Click "New integration"
3. Fill in the integration name and select the associated workspace
4. After creation, copy the "Internal Integration Token"

## Compatibility

* Minimum n8n version: 0.126.0
* Tested versions: 0.126.0 and above

## Usage

1. Add the "Notion to Markdown" node to your workflow
2. Configure the Notion API credentials
3. Enter the Notion page ID you want to convert
4. Run the node to get the converted Markdown content

## Resources

* [n8n community nodes documentation](https://docs.n8n.io/integrations/community-nodes/)
* [Notion API documentation](https://developers.notion.com/reference)
