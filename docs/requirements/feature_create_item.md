# Feature: Create Item

## User Story

As a wardrobe owner, I want to create a new item with its basic information, so that I can keep my wardrobe collection organized.

## Acceptance Criteria

### AC1: Successfully create an item with valid data
**Given** the user is on the item creation form  
**When** the user enters a valid name, optional description, and selects a color  
**Then** a new item is created and saved in the system

### AC2: Prevent creating an item without a name
**Given** the user is on the item creation form  
**When** the user submits the form without entering a name  
**Then** the system rejects the request and shows a validation error for the name field

### AC3: Show the created item in the collection
**Given** a new item has been successfully created  
**When** the user opens the wardrobe item list  
**Then** the newly created item appears in the collection with its name, description, and color
