# myonlineedu-nodejs-mysql-docker
Code example for Node.js and MySQL and PHPMyAdmin docker container application

## Resources

* [Read MyOnlineEdu Blog for details](https://www.myonlineedu.com/blog/view/14/build-docker-container-for-nodejs-and-mysql-based-application)


sql query

-- phpMyAdmin SQL Dump
-- version 4.7.9
-- https://www.phpmyadmin.net/
--
-- Generation Time: Dec 04, 2018 at 11:50 AM
-- Server version: 5.7.24
-- PHP Version: 7.2.2

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET AUTOCOMMIT = 0;
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `moe_db`
--

-- --------------------------------------------------------

--
-- Table structure for table `MOE_ITEM_T`
--

CREATE TABLE `MOE_ITEM_T` (
  `ITEM_NAME` varchar(50) NOT NULL,
  `ITEM_DESC` varchar(100) NOT NULL,
  `ITEM_ONHAND` int(5) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

--
-- Dumping data for table `MOE_ITEM_T`
--

INSERT INTO `MOE_ITEM_T` (`ITEM_NAME`, `ITEM_DESC`, `ITEM_ONHAND`) VALUES
('TEST-ITEM-1', 'TEST-ITEM-DESC-1', 10),
('TEST-ITEM-2', 'TEST-ITEM-DESC-2', 20);
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
