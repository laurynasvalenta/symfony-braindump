# Dependency Injection

## Official Curriculum

#### Service container
* https://symfony.com/doc/7.0/service_container.html
* https://symfony.com/doc/7.0/service_container/alias_private.html
* https://symfony.com/doc/7.0/service_container/configurators.html
* https://symfony.com/doc/7.0/service_container/definitions.html
* https://symfony.com/doc/7.0/service_container/expression_language.html
* https://symfony.com/doc/7.0/service_container/injection_types.html
* https://symfony.com/doc/7.0/service_container/request.html
* https://symfony.com/doc/7.0/service_container/service_closures.html
* https://symfony.com/doc/7.0/bundles/prepend_extension.html
* https://symfony.com/doc/7.0/service_container/synthetic_services.html
* https://symfony.com/doc/7.0/components/dependency_injection.html
* https://symfony.com/doc/7.0/components/dependency_injection/workflow.html
* https://symfony.com/doc/7.0/components/dependency_injection/compilation.html
#### Built-in services
https://symfony.com/doc/current/service_container/debug.html
#### Configuration parameters
* https://symfony.com/doc/7.0/service_container/import.html
#### Services registration (only with YAML and PHP attributes)
* https://symfony.com/doc/7.0/service_container/lazy_services.html
* https://symfony.com/doc/7.0/service_container/optional_dependencies.html
* https://symfony.com/doc/7.0/service_container/parent_services.html
#### Service decoration
* https://symfony.com/doc/7.0/service_container/service_decoration.html
#### Tags
* https://symfony.com/doc/7.0/reference/dic_tags.html
#### Semantic configuration
* https://symfony.com/doc/7.0/components/config/definition.html
* https://symfony.com/doc/7.0/components/config/caching.html
* https://symfony.com/doc/7.0/components/config/resources.html
#### Factories
* https://symfony.com/doc/7.0/service_container/factories.html
#### Compiler passes
* https://symfony.com/doc/7.0/service_container/compiler_passes.html
#### Services autowiring
* https://symfony.com/doc/7.0/service_container/autowiring.html
#### Service locators
* https://symfony.com/doc/7.0/service_container/service_subscribers_locators.html

## Additional Information

#### Events
_None_

#### Constants
* `Symfony\Component\DependencyInjection\ContainerInterface::RUNTIME_EXCEPTION_ON_INVALID_REFERENCE`
* `Symfony\Component\DependencyInjection\ContainerInterface::EXCEPTION_ON_INVALID_REFERENCE`
* `Symfony\Component\DependencyInjection\ContainerInterface::NULL_ON_INVALID_REFERENCE`
* `Symfony\Component\DependencyInjection\ContainerInterface::IGNORE_ON_INVALID_REFERENCE`
* `Symfony\Component\DependencyInjection\ContainerInterface::IGNORE_ON_UNINITIALIZED_REFERENCE`
* `Symfony\Component\DependencyInjection\Compiler\PassConfig::TYPE_AFTER_REMOVING`
* `Symfony\Component\DependencyInjection\Compiler\PassConfig::TYPE_BEFORE_OPTIMIZATION`
* `Symfony\Component\DependencyInjection\Compiler\PassConfig::TYPE_BEFORE_REMOVING`
* `Symfony\Component\DependencyInjection\Compiler\PassConfig::TYPE_OPTIMIZE`
* `Symfony\Component\DependencyInjection\Compiler\PassConfig::TYPE_REMOVE`

#### Attributes
* `Symfony\Component\DependencyInjection\Attribute\Autoconfigure`
* `Symfony\Component\DependencyInjection\Attribute\AsAlias`
* `Symfony\Component\DependencyInjection\Attribute\Target`
* `Symfony\Component\DependencyInjection\Attribute\Autowire`
* `Symfony\Component\DependencyInjection\Attribute\AutowireServiceClosure`
* `Symfony\Component\DependencyInjection\Attribute\AutowireCallable`
* `Symfony\Contracts\Service\Attribute\Required`

#### Interfaces
* `Symfony\Component\Config\Definition\ConfigurationInterface`
* `Symfony\Component\Config\Loader\LoaderInterface`
* `Symfony\Component\DependencyInjection\Compiler\CompilerPassInterface`
* `Symfony\Component\DependencyInjection\ContainerInterface`
* `Symfony\Component\DependencyInjection\EnvVarLoaderInterface`
* `Symfony\Component\DependencyInjection\EnvVarProcessorInterface`
* `Symfony\Component\DependencyInjection\Extension\ExtensionInterface`
* `Symfony\Component\DependencyInjection\Extension\PrependExtensionInterface`
* `Symfony\Component\DependencyInjection\ParameterBag\ContainerBagInterface`
