# Bookmarking
In R, bookmarking in Shiny applications is a feature that lets users save the current state of an app, allowing them to return to it later or share it with others. This feature is especially useful when users want to save customized settings, inputs, or configurations they have applied within an app, so they can resume their work at a later time or provide someone else with access to the same view or analysis.

Bookmarking works by capturing the values of all user inputs at a specific point in time and encoding them into a unique URL. This URL acts as a "bookmark," representing the app’s exact state, which users can open again to restore all previously set inputs. There are two main types of bookmarking in Shiny: URL-based and server-based.

URL-based bookmarking encodes the app state directly within the URL as query parameters. This approach is convenient because the URL can be easily shared, and users don’t need a server to manage saved states. However, URL-based bookmarking has limitations, such as a restricted data size due to URL length constraints, making it suitable for small app states.
