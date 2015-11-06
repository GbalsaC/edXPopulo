# edx-theme


If you’re using Open edX’s [configuration ansible playbooks](https://github.com/edx/configuration), you’ll just need to set

```yml
edxapp_theme_source_repo: https://github.com/your-user/your-repo.git
edxapp_theme_version: your-tag
edxapp_theme_name: $WHATEVER     # from earlier
edxapp_use_custom_theme: true
```

See Open edX’s documentation on [custom theming](https://github.com/edx/edx-platform/wiki/Custom-Theming) for more
information.

## License

[AGPL](http://en.wikipedia.org/wiki/Affero_General_Public_License)
