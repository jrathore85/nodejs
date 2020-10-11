# nodejs
connect db with Nodejs with Db

CREATE TABLE `users` (
  `id` int(10) UNSIGNED PRIMARY KEY NOT NULL AUTO_INCREMENT,
  `fullName` varchar(255) DEFAULT NULL,
  `emailAddress` varchar(255) DEFAULT NULL,
  `city` varchar(255) DEFAULT NULL,
   `country` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL default '1900-01-01 00:00:00'
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
