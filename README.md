# creaditmanagement-app
DROP TABLE `Contacts`;
CREATE TABLE `Contacts` (
`id` mediumint(8) unsigned NOT NULL auto_increment,
`id` mediumint,
`name` varchar(255) default NULL,
`phone` varchar(100) default NULL,
 PRIMARY KEY (`id`)
) AUTO_INCREMENT=1;
INSERT INTO `Contacts` (`id`,`name`,`phone`) VALUES (1,"Hendrix, Pearl S.","1-819-540-1280"),(2,"Berry, Alvin Q.","1-377-410-8722"),(3,"Miles, Libby X.","1-124-185-4488"),(4,"Ball, Myra X.","1-985-899-9850"),(5,"Valdez, Alec X.","1-740-747-9582"),(6,"Bradford, Darrel F.","1-842-399-7226"),(7,"Collins, Oscar N.","1-311-641-2812"),(8,"Head, Lucas O.","1-184-605-4695"),(9,"Malone, Hector S.","1-501-885-9937"),(10,"Brooks, Acton L.","1-465-851-5624");
INSERT INTO `Contacts` (`id`,`name`,`phone`) VALUES (11,"Guy, Mia S.","1-347-952-7094"),(12,"Lawrence, Neve S.","1-124-741-8497"),(13,"Beasley, Shaeleigh J.","1-799-969-4582"),(14,"Ewing, Nomlanga R.","1-485-217-8168"),(15,"Cervantes, Xerxes D.","1-384-668-0693"),(16,"Medina, Quintessa L.","1-937-993-7824"),(17,"Horn, Giacomo X.","1-486-346-9084"),(18,"Wilcox, Leah O.","1-895-253-9538"),(19,"Nieves, Raven D.","1-804-394-9566"),(20,"Conway, Asher Q.","1-372-983-0293");
INSERT INTO `Contacts` (`id`,`name`,`phone`) VALUES (21,"Yang, Colorado I.","1-511-306-1648"),(22,"Fischer, Hayden A.","1-972-925-2899"),(23,"Barnett, Tallulah T.","1-577-399-6069"),(24,"Mathews, Naomi P.","1-863-242-9204"),(25,"Pollard, Baxter I.","1-913-913-9868"),(26,"Kent, Zenaida I.","1-833-380-8623"),(27,"Woods, Jael Z.","1-545-184-8330"),(28,"Stephenson, Emi N.","1-552-295-0886"),(29,"Valdez, Kermit L.","1-588-428-5663"),(30,"Hewitt, Bo Y.","1-232-290-7403");
INSERT INTO `Contacts` (`id`,`name`,`phone`) VALUES (31,"Stein, Fitzgerald W.","1-100-175-8282"),(32,"Mcneil, Calvin C.","1-610-366-2729"),(33,"Rush, Yoko B.","1-814-631-3885"),(34,"Andrews, Frances L.","1-799-467-9282"),(35,"Hanson, John A.","1-417-766-4080"),(36,"Livingston, Britanni W.","1-921-327-9161"),(37,"Little, Olympia X.","1-255-889-9341"),(38,"Mercer, Lane R.","1-350-951-4963"),(39,"William, Aimee M.","1-389-231-3574"),(40,"Bolton, Aladdin T.","1-894-115-3398");
INSERT INTO `Contacts` (`id`,`name`,`phone`) VALUES (41,"Aguirre, Kasimir I.","1-109-230-3901"),(42,"Richardson, Quentin L.","1-698-950-8081"),(43,"Hendricks, Kimberley M.","1-845-495-0908"),(44,"Cabrera, Macey D.","1-711-237-7242"),(45,"Curry, Quamar B.","1-964-364-8705"),(46,"Byers, Emerson E.","1-753-596-1294"),(47,"Kane, Oleg W.","1-234-991-8785"),(48,"Rocha, Stacey W.","1-677-589-6638"),(49,"Keith, Pandora L.","1-225-998-5770"),(50,"Matthews, Alvin C.","1-965-926-4124");
INSERT INTO `Contacts` (`id`,`name`,`phone`) VALUES (51,"Cunningham, Kathleen M.","1-490-181-5405"),(52,"Brady, Florence Q.","1-258-488-6656"),(53,"Long, Mikayla Y.","1-129-458-7306"),(54,"Best, Echo L.","1-699-252-4558"),(55,"Collier, Fay N.","1-548-896-4768"),(56,"Richmond, Philip X.","1-660-798-1821"),(57,"Mckenzie, Shelby R.","1-918-744-3510"),(58,"Simon, Logan H.","1-404-675-3706"),(59,"Tate, Kimberly O.","1-179-769-1032"),(60,"Obrien, Shafira Q.","1-746-376-3407");
INSERT INTO `Contacts` (`id`,`name`,`phone`) VALUES (61,"Schultz, Calvin M.","1-662-534-1231"),(62,"Fox, Ayanna Z.","1-753-949-4097"),(63,"Meadows, Leo M.","1-682-122-7412"),(64,"Crane, Troy E.","1-902-542-3706"),(65,"Holman, Allistair C.","1-603-282-4495"),(66,"Morrison, Brody H.","1-453-218-3332"),(67,"Pace, Helen I.","1-850-783-0033"),(68,"Weiss, Hamish D.","1-226-226-4138"),(69,"Blake, Aretha Y.","1-446-476-8071"),(70,"Holloway, Jordan S.","1-427-322-6127");
INSERT INTO `Contacts` (`id`,`name`,`phone`) VALUES (71,"Park, Alisa K.","1-692-156-6333"),(72,"Johnston, Quentin F.","1-205-676-8260"),(73,"Harding, Cynthia I.","1-873-228-7235"),(74,"Page, Solomon E.","1-545-828-9572"),(75,"Palmer, Echo V.","1-918-859-4018"),(76,"Harrell, Tanner E.","1-499-257-4502"),(77,"Skinner, Suki U.","1-961-404-7291"),(78,"Dejesus, Rhea F.","1-831-320-7911"),(79,"Russo, Warren P.","1-312-827-0627"),(80,"Santiago, Tamekah J.","1-171-963-7029");
INSERT INTO `Contacts` (`id`,`name`,`phone`) VALUES (81,"Woodward, Jessica R.","1-338-936-9717"),(82,"Johnston, Hashim R.","1-751-280-2675"),(83,"Whitaker, Paula I.","1-188-507-9832"),(84,"Bowers, Howard R.","1-531-910-0069"),(85,"Vargas, Richard H.","1-155-111-5445"),(86,"Huff, Jameson W.","1-813-378-2485"),(87,"Frazier, Bree M.","1-411-244-9929"),(88,"Bates, Mason C.","1-232-718-3960"),(89,"Hunt, Abbot Y.","1-745-484-6656"),(90,"Cardenas, Brian B.","1-158-322-4049");
INSERT INTO `Contacts` (`id`,`name`,`phone`) VALUES (91,"Acevedo, Oliver G.","1-263-970-2510"),(92,"Coleman, Thomas E.","1-857-452-8368"),(93,"Daugherty, Melodie K.","1-517-992-4097"),(94,"Richard, Quamar D.","1-368-673-8854"),(95,"Stuart, Samson G.","1-320-906-2033"),(96,"Alvarez, Dai S.","1-855-173-8264"),(97,"Leblanc, Tatum T.","1-355-242-1648"),(98,"Boyle, Walker R.","1-806-134-3594"),(99,"Sullivan, Whilemina P.","1-243-818-9279"),(100,"Shannon, Darryl H.","1-492-166-2593");
