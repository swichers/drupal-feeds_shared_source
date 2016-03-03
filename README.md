Provides a [Feeds][1] node processor that allows more than one Feed to update a single node.

Feeds, by default, will treat GUIDs as unique to the Feed nid *and* the Feed importer ID. This prevents different importers from updating the same node despite them using the same GUID. This module will allow you to configure that functionality on the node processor configuration screen.

## Requirements

* [Feeds][1]

## Usage

Usage of this plugin is fairly straightforward. Enable it as you would any other module. A new Feed processor type will be available for selection. It is the same as the standard node processor with the addition of a few options.

[1]: http://drupal.org/project/feeds
