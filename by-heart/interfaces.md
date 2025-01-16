# Interfaces

The following interfaces are listed in the Symfony docs and are relevant to the Symfony Certification exam.

* `Symfony\Bridge\Doctrine\Security\User\UserLoaderInterface`

* `Symfony\Bundle\FrameworkBundle\Routing\RouteLoaderInterface`

* `Symfony\Component\AssetMapper\AssetMapperInterface`

* `Symfony\Component\Asset\PackageInterface`
* `Symfony\Component\Asset\VersionStrategy\VersionStrategyInterface`

* `Symfony\Component\Cache\Marshaller\MarshallerInterface`
* `Symfony\Component\Cache\PruneableInterface`

* `Symfony\Component\Clock\ClockInterface`

* `Symfony\Component\Config\Definition\ConfigurationInterface`
* `Symfony\Component\Config\Loader\LoaderInterface`

* `Symfony\Component\Console\CommandLoader\CommandLoaderInterface`
* `Symfony\Component\Console\Command\SignalableCommandInterface`
* `Symfony\Component\Console\Input\InputInterface`
* `Symfony\Component\Console\Output\ConsoleOutputInterface`
* `Symfony\Component\Console\Output\OutputInterface`
* `Symfony\Component\Console\Style\StyleInterface`

* `Symfony\Component\DependencyInjection\Compiler\CompilerPassInterface`
* `Symfony\Component\DependencyInjection\ContainerInterface`
* `Symfony\Component\DependencyInjection\EnvVarLoaderInterface`
* `Symfony\Component\DependencyInjection\EnvVarProcessorInterface`
* `Symfony\Component\DependencyInjection\Extension\ExtensionInterface`
* `Symfony\Component\DependencyInjection\Extension\PrependExtensionInterface`
* `Symfony\Component\DependencyInjection\ParameterBag\ContainerBagInterface`

* `Symfony\Component\EventDispatcher\EventSubscriberInterface`

* `Symfony\Component\ExpressionLanguage\ExpressionFunctionProviderInterface`

* `Symfony\Component\Filesystem\Exception\ExceptionInterface`
* `Symfony\Component\Filesystem\Exception\IOExceptionInterface`

* `Symfony\Component\Form\ChoiceList\Loader\ChoiceLoaderInterface`
* `Symfony\Component\Form\DataMapperInterface`
* `Symfony\Component\Form\DataTransformerInterface`
* `Symfony\Component\Form\FormBuilderInterface`
* `Symfony\Component\Form\FormFactoryInterface`
* `Symfony\Component\Form\FormInterface`
* `Symfony\Component\Form\FormTypeExtensionInterface`
* `Symfony\Component\Form\FormTypeGuesserInterface`
* `Symfony\Component\Form\FormTypeInterface`

* `Symfony\Component\HtmlSanitizer\HtmlSanitizerInterface`
* `Symfony\Component\HtmlSanitizer\Visitor\AttributeSanitizer\AttributeSanitizerInterface`

* `Symfony\Component\HttpClient\Response\StreamableInterface`
* `Symfony\Component\HttpClient\Retry\RetryStrategyInterface`

* `Symfony\Component\HttpFoundation\Exception\RequestExceptionInterface`
* `Symfony\Component\HttpFoundation\RateLimiter\RequestRateLimiterInterface`
* `Symfony\Component\HttpFoundation\RequestMatcherInterface`
* `Symfony\Component\HttpFoundation\Session\SessionInterface`
* `Symfony\Component\HttpFoundation\Session\Storage\SessionStorageFactoryInterface`

* `Symfony\Component\HttpKernel\CacheClearer\CacheClearerInterface`
* `Symfony\Component\HttpKernel\CacheWarmer\CacheWarmerInterface`
* `Symfony\Component\HttpKernel\Controller\ArgumentResolverInterface`
* `Symfony\Component\HttpKernel\Controller\ControllerResolverInterface`
* `Symfony\Component\HttpKernel\Controller\ValueResolverInterface`
* `Symfony\Component\HttpKernel\DataCollector\DataCollectorInterface`
* `Symfony\Component\HttpKernel\DataCollector\LateDataCollectorInterface`
* `Symfony\Component\HttpKernel\Exception\HttpExceptionInterface`
* `Symfony\Component\HttpKernel\Fragment\FragmentRendererInterface`
* `Symfony\Component\HttpKernel\HttpKernelInterface`
* `Symfony\Component\HttpKernel\KernelInterface`
* `Symfony\Component\HttpKernel\TerminableInterface`

* `Symfony\Component\Ldap\Adapter\AdapterInterface`
* `Symfony\Component\Ldap\Adapter\QueryInterface`

* `Symfony\Component\Lock\BlockingStoreInterface`
* `Symfony\Component\Lock\PersistingStoreInterface`
* `Symfony\Component\Lock\SharedLockStoreInterface`

* `Symfony\Component\Mailer\Exception\TransportExceptionInterface`
* `Symfony\Component\Mailer\MailerInterface`
* `Symfony\Component\Mailer\Transport\TransportFactoryInterface`
* `Symfony\Component\Mailer\Transport\TransportInterface`

* `Symfony\Component\Mercure\HubInterface`
* `Symfony\Component\Mercure\Jwt\TokenProviderInterface`

* `Symfony\Component\Messenger\Bridge\AmazonSqs\MessageDeduplicationAwareInterface`
* `Symfony\Component\Messenger\Bridge\AmazonSqs\MessageGroupAwareInterface`
* `Symfony\Component\Messenger\Handler\BatchHandlerInterface`
* `Symfony\Component\Messenger\MessageBusInterface`
* `Symfony\Component\Messenger\Middleware\MiddlewareInterface`
* `Symfony\Component\Messenger\Middleware\StackInterface`
* `Symfony\Component\Messenger\Stamp\StampInterface`
* `Symfony\Component\Messenger\Transport\Receiver\MessageCountAwareInterface`
* `Symfony\Component\Messenger\Transport\Receiver\QueueReceiverInterface`
* `Symfony\Component\Messenger\Transport\Receiver\ReceiverInterface`
* `Symfony\Component\Messenger\Transport\Sender\SenderInterface`
* `Symfony\Component\Messenger\Transport\Serialization\SerializerInterface`
* `Symfony\Component\Messenger\Transport\TransportFactoryInterface`
* `Symfony\Component\Messenger\Transport\TransportInterface`

* `Symfony\Component\Mime\BodyRendererInterface`
* `Symfony\Component\Mime\HtmlToTextConverter\HtmlToTextConverterInterface`
* `Symfony\Component\Mime\MimeTypeGuesserInterface`

* `Symfony\Component\PasswordHasher\Hasher\PasswordHasherAwareInterface`
* `Symfony\Component\PasswordHasher\Hasher\UserPasswordHasherInterface`
* `Symfony\Component\PasswordHasher\LegacyPasswordHasherInterface`
* `Symfony\Component\PasswordHasher\PasswordHasherInterface`

* `Symfony\Component\PropertyInfo\PropertyAccessExtractorInterface`
* `Symfony\Component\PropertyInfo\PropertyDescriptionExtractorInterface`
* `Symfony\Component\PropertyInfo\PropertyDocBlockExtractorInterface`
* `Symfony\Component\PropertyInfo\PropertyInitializableExtractorInterface`
* `Symfony\Component\PropertyInfo\PropertyListExtractorInterface`
* `Symfony\Component\PropertyInfo\PropertyTypeExtractorInterface`

* `Symfony\Component\RateLimiter\LimiterInterface`
* `Symfony\Component\RateLimiter\Storage\StorageInterface`

* `Symfony\Component\RemoteEvent\Consumer\ConsumerInterface`

* `Symfony\Component\Routing\Generator\UrlGeneratorInterface`
* `Symfony\Component\Routing\Matcher\UrlMatcherInterface`
* `Symfony\Component\Routing\RouterInterface`

* `Symfony\Component\Runtime\ResolverInterface`
* `Symfony\Component\Runtime\RunnerInterface`
* `Symfony\Component\Runtime\RuntimeInterface`

* `Symfony\Component\Scheduler\ScheduleProviderInterface`
* `Symfony\Component\Scheduler\Trigger\TriggerInterface`

* `Symfony\Component\Security\Core\Authentication\AuthenticationTrustResolverInterface`
* `Symfony\Component\Security\Core\Authentication\RememberMe\TokenProviderInterface`
* `Symfony\Component\Security\Core\Authentication\Token\TokenInterface`
* `Symfony\Component\Security\Core\Authentication\User\UserInterface`
* `Symfony\Component\Security\Core\Authorization\AccessDecisionManagerInterface`
* `Symfony\Component\Security\Core\Authorization\AuthorizationCheckerInterface`
* `Symfony\Component\Security\Core\Authorization\Strategy\AccessDecisionStrategyInterface`
* `Symfony\Component\Security\Core\Authorization\Voter\CacheableVoterInterface`
* `Symfony\Component\Security\Core\Authorization\Voter\VoterInterface`
* `Symfony\Component\Security\Core\User\AttributesBasedUserProviderInterface`
* `Symfony\Component\Security\Core\User\EquatableInterface`
* `Symfony\Component\Security\Core\User\PasswordAuthenticatedUserInterface`
* `Symfony\Component\Security\Core\User\PasswordUpgraderInterface`
* `Symfony\Component\Security\Core\User\UserCheckerInterface`
* `Symfony\Component\Security\Core\User\UserInterface`
* `Symfony\Component\Security\Core\User\UserProviderInterface`
* `Symfony\Component\Security\Http\AccessToken\AccessTokenExtractorInterface`
* `Symfony\Component\Security\Http\AccessToken\AccessTokenHandlerInterface`
* `Symfony\Component\Security\Http\Authentication\AuthenticationFailureHandlerInterface`
* `Symfony\Component\Security\Http\Authentication\AuthenticationSuccessHandlerInterface`
* `Symfony\Component\Security\Http\Authenticator\AuthenticatorInterface`
* `Symfony\Component\Security\Http\Authenticator\InteractiveAuthenticatorInterface`
* `Symfony\Component\Security\Http\Authorization\AccessDeniedHandlerInterface`
* `Symfony\Component\Security\Http\EntryPoint\AuthenticationEntryPointInterface`
* `Symfony\Component\Security\Http\LoginLink\LoginLinkHandlerInterface`
* `Symfony\Component\Security\Http\RememberMe\RememberMeHandlerInterface`

* `Symfony\Component\Serializer\Context\ContextBuilderInterface`
* `Symfony\Component\Serializer\Encoder\DecoderInterface`
* `Symfony\Component\Serializer\Encoder\EncoderInterface`
* `Symfony\Component\Serializer\Mapping\ClassDiscriminatorResolverInterface`
* `Symfony\Component\Serializer\NameConverter\AdvancedNameConverterInterface`
* `Symfony\Component\Serializer\NameConverter\NameConverterInterface`
* `Symfony\Component\Serializer\Normalizer\DenormalizerAwareInterface`
* `Symfony\Component\Serializer\Normalizer\DenormalizerInterface`
* `Symfony\Component\Serializer\Normalizer\NormalizableInterface`
* `Symfony\Component\Serializer\Normalizer\NormalizerInterface`
* `Symfony\Component\Serializer\SerializerInterface`

* `Symfony\Component\String\Inflector\InflectorInterface`
* `Symfony\Component\String\Slugger\SluggerInterface`

* `Symfony\Component\Translation\Dumper\DumperInterface`
* `Symfony\Component\Translation\Extractor\ExtractorInterface`
* `Symfony\Component\Translation\Formatter\MessageFormatterInterface`
* `Symfony\Component\Translation\Loader\LoaderInterface`
* `Symfony\Component\Translation\Provider\ProviderFactoryInterface`
* `Symfony\Component\Translation\Provider\ProviderInterface`

* `Symfony\Component\Validator\ConstraintValidatorInterface`
* `Symfony\Component\Validator\ConstraintViolationListInterface`
* `Symfony\Component\Validator\Context\ExecutionContextInterface`
* `Symfony\Component\Validator\GroupProviderInterface`
* `Symfony\Component\Validator\GroupSequenceProviderInterface`
* `Symfony\Component\Validator\Mapping\Factory\MetadataFactoryInterface`
* `Symfony\Component\Validator\ObjectInitializerInterface`
* `Symfony\Component\Validator\Validator\ValidatorInterface`
* `Symfony\Component\Validator\Violation\ConstraintViolationBuilderInterface`

* `Symfony\Component\VarDumper\Cloner\DumperInterface`
* `Symfony\Component\VarDumper\Dumper\DataDumperInterface`

* `Symfony\Component\Workflow\MarkingStore\MarkingStoreInterface`
* `Symfony\Component\Workflow\WorkflowInterface`

* `Symfony\Contracts\Cache\CacheInterface`
* `Symfony\Contracts\Cache\ItemInterface`
* `Symfony\Contracts\Cache\TagAwareCacheInterface`

* `Symfony\Contracts\EventDispatcher\EventDispatcherInterface`

* `Symfony\Contracts\HttpClient\Exception\DecodingExceptionInterface`
* `Symfony\Contracts\HttpClient\Exception\ExceptionInterface`
* `Symfony\Contracts\HttpClient\Exception\HttpExceptionInterface`
* `Symfony\Contracts\HttpClient\Exception\TransportExceptionInterface`
* `Symfony\Contracts\HttpClient\HttpClientInterface`
* `Symfony\Contracts\HttpClient\ResponseInterface`

* `Symfony\Contracts\Service\ResetInterface`
* `Symfony\Contracts\Service\ServiceCollectionInterface`
* `Symfony\Contracts\Service\ServiceProviderInterface`
* `Symfony\Contracts\Service\ServiceSubscriberInterface`

* `Symfony\Contracts\Translation\LocaleAwareInterface`
* `Symfony\Contracts\Translation\TranslatableInterface`
* `Symfony\Contracts\Translation\TranslatorInterface`
