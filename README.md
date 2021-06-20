# djangotodoapp
django-todo is a pluggable, multi-user, multi-group task management and assignment application for Django, designed to be dropped into an existing site as a reusable app. django-todo can be used as a personal to-do tracker, or a group task management system, or a ticketing system for organizations (or all of these at once!)

The best way to learn how django-todo works is to visit the live demo site at django-todo.org!
## Features
* Drag and drop task prioritization
* Email task notification
* Search
* Comments on tasks
* Public-facing submission form for tickets
* Mobile-friendly (work in progress)
* Separate view for My Tasks (across lists)
* Batch-import tasks via CSV
* Batch-export tasks in CSV Format
* Multiple file attachments per task (see settings)
* Integrated mail tracking (unify a task list with an email box)
## Requirements
* Django 2.0+
* Python 3.6+
* jQuery (full version, not "slim", for drag/drop prioritization)
* Bootstrap (to work with provided templates, though you can override them)
* bleach (pip install bleach)
* django-autocomplete-light (optional, required for task merging)
