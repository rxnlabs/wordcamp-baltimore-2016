## TGM Plugin Activation: How to use it?

```php

add_action( 'tgmpa_register', 'avada_jupiter_divi_plugins' );

function avada_jupiter_divi_plugins() {
	$plugins = array(
			array(
				'name'      => 'Yoast SEO',
				'slug'      => 'wordpress-seo',
				'required'  => false,
			),
			array(
				'name'      => 'Meta Slider',
				'slug'      => 'ml-slider',
				'required'  => true,
			),
			array(
				'name'               => 'Gravity Forms GA Parse Add-On',
				'slug'               => 'gravityforms-gaparse-add-on',
				'source'             => 'https://github.com/rxnlabs/gravityforms-gaparse/archive/master.zip',
				'required'           => true,
				'version'            => '',
				'force_activation'   => false,
				'force_deactivation' => false,
				'external_url'       => '',
				'is_callable'        => '',
			),
		);

	$config = array(
		'id'           => 'ajdp_unique_id',
		'menu'         => 'tgmpa-install-plugins',
		'parent_slug'  => 'themes.php',
		'capability'   => 'edit_theme_options',
		'has_notices'  => true,
		'dismissable'  => true,
	);

	tgmpa( $plugins, $config );
}
```

Note:
Premium theme named Avada Jupiter Divi.

- It's SEO Optimized, built in Slider support, Social Sharing support.
- It uses plugins to make these features work.
- After theme activation, you would go into the Apperance menu -> Install plugins.