---
title: 'Dodaj nowy post'
taxonomy:
    tag:
        - passwdrd
template: form
pageconfig:
    parent: /blog
    include_username: true
    overwrite_mode: true
pagefrontmatter:
    template: item
    title: 'My new Blog post'
    taxonomy:
        category: blog
        tag:
            - informatyka
            - 3d
form:
    name: addpage.blogpost
    fields:
        -
            name: author
            label: Autor
            type: text
        -
            name: title
            label: Tytuł
            type: text
        -
            name: taxonomy.tag
            label: 'Tagi (php,html,css,js,c++) (oddzielaj przecinkami)'
            type: text
        -
            name: content
            label: 'Treść Postu'
            type: textarea
            size: long
            classes: editor
        -
            name: images
            label: Obrazy
            type: file
            multiple: true
            accept:
                - 'image/*'
            destination: '@self'
        -
            name: honeypot
            type: honeypot
    buttons:
        -
            type: submit
            value: Submit
    process:
        -
            addpage: null
        -
            redirect: /blog
---

## Dodaj nowego posta

W tym miejscu napisz treść posta.