---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
featured_image: "/images/projects/{{ .Name }}/featured.png"
links: [
	{
		name: "Example Link",
		icon: "fa-file",
		url: "https://example.com/",
		color: "word-blue"
	}
]
---
