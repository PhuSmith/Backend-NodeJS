INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('ROLE','R1','Admin', 'Quản trị viên',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('ROLE','R2','Doctor', 'Bác sĩ',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('ROLE','R3','Patient', 'Bệnh nhân',0,0 );

INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('STATUS','S1','New', 'Lịch hẹn mới',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('STATUS','S2','Confirmed', 'Đã xác nhận',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('STATUS','S3','Done', 'Đã khám xong',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('STATUS','S4','Cancel', 'Đã hủy',0,0 );

INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('TIME','T1','8:00 AM - 9:00 AM', '8:00 - 9:00',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('TIME','T2','9:00 AM - 10:00 AM', '9:00 - 10:00',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('TIME','T3','10:00 AM - 11:00 AM', '10:00 - 11:00',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('TIME','T4','11:00 AM - 0:00 PM', '11:00 - 12:00',0,0 );

INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('TIME','T5','1:00 PM - 2:00 PM', '13:00 - 14:00',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('TIME','T6','2:00 PM - 3:00 PM', '14:00 - 15:00',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('TIME','T7','3:00 PM - 4:00 PM', '15:00 - 16:00',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('TIME','T8','4:00 PM - 5:00 PM', '16:00 - 17:00',0,0 );

INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('POSITION','P0','None', 'Bác sĩ',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('POSITION','P1','Master', 'Thạc sĩ',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('POSITION','P2','Doctor', 'Tiến sĩ',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('POSITION','P3','Associate Professor', 'Phó giáo sư',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('POSITION','P4','Professor', 'Giáo sư',0,0 );

INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('GENDER','M','Male', 'Nam',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('GENDER','F','Female', 'Nữ',0,0 );
INSERT INTO Allcodes (Allcodes.type,Allcodes.keyMap, Allcodes.valueEn, Allcodes.valueVi, Allcodes.createdAt, Allcodes.updatedAt ) values ('GENDER','O','Other', 'Khác',0,0 );

câu lệnh upload kiểu dữ liệu trong db
npx sequelize-cli db:migrate --to migration-create-user.js
