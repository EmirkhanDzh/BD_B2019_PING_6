1. ��� ��� ��� ������� � ��������� ���������, ����� ��� ������� ������ ����������� ���� �� � ����� ��������. ���� ������� � ���� ����.

2. 1) 
���������: {[<ins> �����_����� </ins>, <ins> ISBN </ins>, ���������_��_�����]}
������_�_������_�����: {[<ins> �����_������ </ins>, ����_�����������, ISBN_������_�����, �����_������_�����, �����_��������]}
�����: {[<ins> ISBN </ins>, ���, ��������, �����, ���������� �������, ���_������������]}
���������: {[<ins> ��� </ins>, ���_�������_���������]}
������������: {[<ins> ��� </ins>], �����}
��������: {[<ins> ����� </ins>, �������, ���, �����, ����_��������]}
���������_�����: {[<ins> ISBN </ins>, <ins> ���_��������� </ins>]}
2.1)
������: {[<ins> �������� </ins>]}
�����: {[<ins> ��������_������ </ins>, <ins> ��������_������ </ins>]}]}
�����: {[<ins> ��������_������ </ins>, <ins> ��������_������ </ins>, <ins> ��������_����� </ins>]}
���: {[<ins> ��������_������ </ins>, <ins> ��������_������ </ins>, <ins> ��������_����� </ins>, <ins> �����_���� </ins>]}
��������: {[<ins> ��������_������ </ins>, <ins> ��������_������ </ins>, <ins> ��������_����� </ins>, <ins> �����_���� </ins>, <ins> �����_�������� </ins>]}
2.2)
������: {[<ins> Id </ins>]}
�������: {[<ins> Id </ins>]}
����: {[<ins> �����_����� </ins>, �������_1, �������_2, ������_id]}
2.3)
�������: {[<ins> id </ins>, ����_id, ����_id]}
�������: {[<ins> id </ins>, ����_id, ����_id]}
3)
��������: {[<ins> ��� </ins>]}
�������: {[<ins> ��� </ins>, <ins> ���_�������� </ins>]}
�����: {[<ins> ��� </ins>, <ins> ��������_1 </ins>, <ins> ��������_2 </ins>, ���]}

3. 
1)
Station: {[<ins> Name </ins>], #Tracks, <ins> City_Name </ins>, <ins> City_Region </ins>]}
City: {[<ins> Name </ins>, <ins> Region </ins>]}
Train: {[<ins> TrainNr </ins>, Length, Start_Station, End_Station]}
Connection: {[Station1_Name, Station1_City_Name, Station1_City_Region, Station2_Name, Station2_City_Name, Station2_City_Region, <ins> Departure </ins>, Arrival, <ins> Train_ID </ins>]}
2)
Room: {[<ins> RoomNr </ins>, <ins> StatNr </ins>, #Beds]}
Patient: {[<ins> PatientNr </ins>, Name, Disease, Doctor_id, RoomNr, from, to]}
Station: {[<ins> StatNr </ins>, Name]}
StationPersonell: {[<ins> PersNr </ins>, <ins> StatNr </ins>, #Name]}
Caregiver: {[<ins> PersNr </ins>, Qualification]}
Doctor: {[<ins> PersNr </ins>, Area, Rank]}

