# Let EAT Go Server


+--------------------+

| Database           |

+--------------------+

| Let_EAT_Go         |

+--------------------+



+----------------------+

| Tables_in_Let_EAT_Go |

+----------------------+

| Partys               |

| Users                |

+----------------------+



##Users



+-------+-------------+------+-----+---------+-------+

| Field | Type        | Null | Key | Default | Extra |

+-------+-------------+------+-----+---------+-------+

| id    | varchar(45) | NO   | PRI | NULL    |       |

| email | varchar(45) | NO   |     | NULL    |       |

+-------+-------------+------+-----+---------+-------+



##Partys



+--------------+-------------+------+-----+---------+-------+

| Field        | Type        | Null | Key | Default | Extra |

+--------------+-------------+------+-----+---------+-------+

| id           | varchar(45) | NO   | PRI | NULL    |       |

| Category     | varchar(45) | NO   |     | NULL    |       |

| Name         | varchar(45) | NO   |     | NULL    |       |

| Joined       | int(11)     | NO   |     | NULL    |       |

| MAXjoin      | int(11)     | NO   |     | NULL    |       |

| time         | datetime    | NO   |     | NULL    |       |

| host         | varchar(45) | NO   |     | NULL    |       |

| Participant1 | varchar(45) | YES  |     | NULL    |       |

| Participant2 | varchar(45) | YES  |     | NULL    |       |

| Participant3 | varchar(45) | YES  |     | NULL    |       |

+--------------+-------------+------+-----+---------+-------+
