	
		// 1. trzeba wyczyscic baze myFirstDB_test (delete all tabeles)
		// 2. zrobic przebieg zakładajacy tabele - we wszestkich klsach testowych @Transactional musi być odkomentowany
		// przebieg odpalamy poprzez: run  java application
		/* i potem odpalic ten skrytp zakładajacy dane do mocka
INSERT INTO public.site_user
(id, email, enabled, firstname, "password", "role", surname)
VALUES(170, 'aa@wp.pl', true, 'aa', 'aa', 'ADMIN_ROLE', 'aa');


INSERT INTO public.interests
(id, interest_name)
VALUES(168, 'some interest here');


INSERT INTO public.profile
(id, about, photo_directory, photo_extension, photo_name, user_id)
VALUES(244, '', '', '', '', 170);

INSERT INTO public.profile_interests
(profile_id, interest_id)
VALUES(244, 168);
commit;
		 */
