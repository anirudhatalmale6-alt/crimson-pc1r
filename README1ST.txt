Once project is created  named  PC1R
Create displays as requested here
Will provide Bonus to project for payment


Need display to show status of these tags
Because Crimsion will not import I/O points  these aliases were created

Need displays to show status of these tags


ALIAS,,OutputModule3,"Output Image For Crimson 3.2 to import image of Output module in SLot 3","","Local:3:O","(ExternalAccess := Read/Write)"
OutputModule3 OF Local:3:O (Description := "Output Image For Crimson 3.2 to import image of Output module in SLot 3",
COMMENT.DATA.0 := "VICES_CLOSE_SOL",
COMMENT.DATA.1 := "WALK BEAM UP SOL Walking Beam UpSolenoid",
COMMENT.DATA.2 := "WALK BEAM FWD SOL Walking Beam Forward Solenoid",
COMMENT.DATA.3 := "MARK HEAD DOWN SOL Marking Head Down Solenoid",
COMMENT.DATA.4 := "MARK HEAD FWD SOL Marking Head Forward Solenoid",
COMMENT.DATA.5 := "MARK HEAD ROD KICKER",
COMMENT.DATA.6 := "COUNT",
COMMENT.DATA.7 := "POINT ADVANCE SOL",
COMMENT.DATA.8 := "CHAMFER ADV SOLChamfer Advance Solenoid",
COMMENT.DATA.9 := "AUTO_PILOT_LT",
COMMENT.DATA.10 := "FAULT_PILOT_LT",
COMMENT.DATA.11 := "BEACON_PILOT_LT",
COMMENT.DATA.12 := "MS1 Point Motor StarterCoil",
COMMENT.DATA.13 := "MS2 Chamfer MotorStarter Coil",
COMMENT.DATA.14 := "MS3 Coolant Pump MotorStarter Coil");
ALIAS,,InputModule1,"Input Image For Crimson 3.2 to import image of Inout module in SLot 1","","Local:1:I","(ExternalAccess := Read/Write)"
COMMENT,,InputModule1,"ESR Emergency Stop Relay Input",,"InputModule1.DATA.0"
COMMENT,,InputModule1,"MS1 MS2 AUX Point & Chamfer Motor Starter Auxiliaries In Series",,"InputModule1.DATA.1"
COMMENT,,InputModule1,"AUTO STOP PB Operator Auto Stop PB",,"InputModule1.DATA.2"
COMMENT,,InputModule1,"MS3 AUX Coolant Pump Motor Starter Auxiliary",,"InputModule1.DATA.3"
COMMENT,,InputModule1,"Auto Manual Selector Switch$NManual_Selected",,"InputModule1.DATA.4"
COMMENT,,InputModule1,"AUTO START PB",,"InputModule1.DATA.5"
COMMENT,,InputModule1,"POINT MANUAL PB",,"InputModule1.DATA.6"
COMMENT,,InputModule1,"CHAMFER MANUAL PB",,"InputModule1.DATA.7"
COMMENT,,InputModule1,"VICES_CLOSE_PB",,"InputModule1.DATA.8"
COMMENT,,InputModule1,"VICES_OPEN_PB",,"InputModule1.DATA.9"
ALIAS,,InputModule2,"Input Image For Crimson 3.2 to import image of Inout module in SLot 2","","Local:2:I","(ExternalAccess := Read/Write)"
COMMENT,,InputModule2,"PROX1 Rod In Position to Clamp",,"InputModule2.DATA.0"
COMMENT,,InputModule2,"PROX2 Rod In Position to Mark",,"InputModule2.DATA.1"
COMMENT,,InputModule2,"PROX3 Vice 1 Is Opeen",,"InputModule2.DATA.2"
COMMENT,,InputModule2,"VICES CLOSED PROXES Vices Closed Prox Vice 1 & Prox Vice 2 Wired In Series",,"InputModule2.DATA.3"
COMMENT,,InputModule2,"PROX4 Vice 2 Is Open",,"InputModule2.DATA.4"
COMMENT,,InputModule2,"RESET PB ESR / Fault Reset Button",,"InputModule2.DATA.5"
COMMENT,,InputModule2,"LS1 Point Depth Limit Switch",,"InputModule2.DATA.6"
COMMENT,,InputModule2,"COOLANT ON SW Coolant On Switch",,"InputModule2.DATA.7"
COMMENT,,InputModule2,"LS3 Chamfer Depth Limit Switch",,"InputModule2.DATA.8"
COMMENT,,InputModule2,"HEADS ON SW Cutting Heads On Switch",,"InputModule2.DATA.9"
COMMENT,,InputModule2,"INDEX PB Operator Index PB",,"InputModule2.DATA.10"
COMMENT,,InputModule2,"LS5 Marking Head Home Limit Switch",,"InputModule2.DATA.11"
COMMENT,,InputModule2,"LS6 Marking Head Not Up Limit Switch",,"InputModule2.DATA.12"
COMMENT,,InputModule2,"SW2 P AND C ONLY Point and Chamfer Only No Stamping",,"InputModule2.DATA.13"
COMMENT,,InputModule2,"SW2 STAMP ONLY",,"InputModule2.DATA.14"
COMMENT,,InputModule2,"STAMP PB",,"InputModule2.DATA.15"
ALIAS,,InputModule4,"Input Image For Crimson 3.2 to import image of Inout module in SLot 4","","Local:4:I","(ExternalAccess := Read/Write)"
COMMENT,,InputModule4,"BEAM1 UP FB",,"InputModule4.DATA.0"
COMMENT,,InputModule4,"BEAM1 DOWN FB",,"InputModule4.DATA.1"
COMMENT,,InputModule4,"BEAM1 FWD FB",,"InputModule4.DATA.2"
COMMENT,,InputModule4,"BEAM1 HOME FB",,"InputModule4.DATA.3"
COMMENT,,InputModule4,"BEAM2 UP FB",,"InputModule4.DATA.4"
COMMENT,,InputModule4,"BEAM2 DOWN FB",,"InputModule4.DATA.5"
COMMENT,,InputModule4,"BEAM2 FWD FB",,"InputModule4.DATA.6"
COMMENT,,InputModule4,"BEAM2 HOME FB",,"InputModule4.DATA.7"

Need Alarm tags and displays for these tags
TAG,,N7,"","INT[10]","","(RADIX := Decimal, Constant := false, ExternalAccess := Read/Write)"
COMMENT,,N7,"VICE FAIL 2 CLOSE Fault ",,"N7[0].0"
COMMENT,,N7,"Point Or Chamfer Motor Overload Or Starter Failed MSI or MS2 TRIP Fault ",,"N7[0].1"
COMMENT,,N7,"Cooland Overload Starter Failure MS3 Fault  ",,"N7[0].3"
COMMENT,,N7,"VICE1 FAIL 2 OPEN Fault",,"N7[0].4"
COMMENT,,N7,"Stamp Not Home Fault ",,"N7[0].5"
COMMENT,,N7,"Stamp Down  Fault ",,"N7[0].6"
COMMENT,,N7,"Beam  1 Not Down Fault ",,"N7[0].7"
COMMENT,,N7,"Beam  2 Not Down Fault ",,"N7[0].8"
COMMENT,,N7,"Beam  1 Up Fault ",,"N7[0].9"
COMMENT,,N7,"Beam  2 Up Fault ",,"N7[0].10"
COMMENT,,N7,"Beam  1 Not Down Fault ",,"N7[0].11"
COMMENT,,N7,"Beam  2 Not Down Fault ",,"N7[0].12"
COMMENT,,N7,"Beam  1 Not Up Fault ",,"N7[0].13"
COMMENT,,N7,"Beam  2 Not Up Fault ",,"N7[0].14"
COMMENT,,N7,"Beam  1 Not Home Fault ",,"N7[0].15"
COMMENT,,N7,"Beam  2 Not Home Fault ",,"N7[1].0"
COMMENT,,N7,"Beam  1 Forward  Fault ",,"N7[1].1"
COMMENT,,N7,"Beam  2 Forward  Fault ",,"N7[1].2"
COMMENT,,N7,"Beam  1 Not Forward Fault ",,"N7[1].3"
COMMENT,,N7,"Beam  2 Not Forward Fault ",,"N7[1].4"
COMMENT,,N7,"Beam  1 Home Fault ",,"N7[1].5"
COMMENT,,N7,"Beam  2 Home Fault ",,"N7[1].6"
COMMENT,,N7,"No Rods Fault ",,"N7[1].7"
COMMENT,,N7,"VICE2 FAIL 2 OPEN Fault ",,"N7[1].8"
COMMENT,,N7,"Month Saved",,"N7[3]"
COMMENT,,N7,"Day Saved",,"N7[4]"