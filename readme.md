log4php
=======
php统一日志记录

require_once(LOG4PHP_DIR."Logger.php");

Logger::configure(LOG4PHP_DIR."log4php.properties");

$logger = Logger::getRootLogger();

$logger->debug("test);