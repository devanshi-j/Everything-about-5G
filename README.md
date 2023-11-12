# Everything-about-5G

# Module 1
Steps to get started
1.once network designed
2. It gets deployed by service provider
3.Then it's checked one more time, for the need of optimisation. To derive the best user experience

* wireless communications & cellular networks

Basic concept states communication between transmiter and reciever without any physical contact.


1. Communication takes place by wireless channel, with the help of signals.
(Antena plays a major role to achive the above stated above.

* mostly every device can act transmitter & reciever both.

*Wireless signals (Radio frequency signals) 

#Radio signal properties

1.wireless signal travels at the speed of light ~ 300000 km /sec

2. Two main properties:
   I.frequency = speed of light/wavelength.
   It is the no. of repetition of radio       signals in 1 second. It is measured in     Hertz (Hz).
   RANGE: 3KHz-300GHz

   II. A wavelength fo measured in (m).       is the distance a wave travels to          complete a full cycle.
   RANGE: 100Km-1Mm

*frequency increases and wavelength decreaces. And Vica Versa.

NOTE: If 2 Radio Signals have same frequency they they will have same wavelength.

*Radio signals (electro magnetic signals)
also known as carrier waves.

* Modulation is to impose info, an the carrier waves. It can change certain atteributes like wavelength of the CW, this is how it imposes information onto the carrier. It can be analog  or digital

*demodulation is recovering the data from the reciever.

MODEM 
(MO = modulation, DEM = demodulation).

* what happens during, phone conversation; wireless transmission & reception

*While sending a message
sound
 ⬇️
Modulation, imposed to carrier ware
 ⬇️
power amplification 
(more power = better coverage area)
 ⬇️
 Antena

VICA VERSA HAPPENS WHILE RECIEVEING A MESSAGE.

*While transfering of information it faces some challanges:
• Attenuates / Path loss transmission loss.
• Noise & interference

* In real time
  device 1 ➡️ ANTENA ➡️ device 2...

Noise & Interference (unwanted signals or energies..)

INTERGERENCE: delibrate form of disturbing energies. When 2 towers use the same redio frequency this happens.

NOISE: 
unwanted signal not delebrate. Already present in the device (Thermal noise).
It cannot be minimized after a certain level.

*Ambient noise (can be eliminated)

*To find a quatitative value

1.SNR Signal: Signal/Noise
(signal to noise ratio)

2. SINR: signal/ Noise + interference  (Signal tointerference & noise ratio).

# Radio Spectrum
is range of radio frequencies for which wireless connection takes place for a specific reason.

RANGE: 450 MHZ - 39 GHz
                   ⬇️
                 mmWave


*There are companies that assign transmission to different radio spectrums

# Radio channel and bandwidth

• when Phone transfers information, it just uses part of radio signal. It limited range of frequency known as its radio/frequency channel & its width is called bandwidth.

Radio Channel
1. narrowband: small amount of redio spectrum

2. Wideband: large amount of radio spectrum

Qs) why can't every every channel be wideband 
Ans. because of lack of avalibility, cause if radio spectrum is more then expence is also more.

*CDMA (Code division Multiple access)
2 ways of sharing
•TDD (Time division duplexing)
    A single radio channel is used, but       at different time. As speed of data       decreses, expences increase.
•FDD (Fequency division duplexing)
    two different channels are use to         communicate one is assigned tower         other your phone. But, It is              expensive and needs abundent radio 
    spectrum

* Factors affecting data rate
1.SNR
how good connectivity is shown by the bars.

2. How wide & crowded the channel is

3. How frequently abd efficiently the phone can utilize the channel, also known a spectral efficiency.

TOWERS = BASE STATION

* The cellular concept (main aim is to decrease dropped cells abd increase data rates and coverage area.)

According to the cellular concept mobile network coverage areas are divided into cells. According to geographical areas

• Hand off it states that you cellular tower changes, when your location changes.

If you are in a at low coverage area, it will affect your connection (known as dropped cells)

* what is cellular network

Services (email, Internet etc)
 ⬇️
Core network
It contains the data and also serves as the routing bridge between RAN & services.
 ⬇️
Towers everywhere 
RAN - Radio Access Network
 ⬇️
data reaches to phones...

# MODULE 2
How cellular communication are evolved over the years 1980's

1G- idea: people can recieve & make calls keeping aside there location. Done through analog modulation (anolog voice).

2G - 1990's - Idea: Same as 1G & also texts Started. Uses digital voice (digital modulation)

Advantages of using digital voica:
1.Compress
2.Reproduce & tramit digital sound

2000's - 3G idea - seamles access to internet

4G - when it came, the speed of data increased. But, it also expanded the eco system of gagets like Tabs, VR's ete, came into existance.

* 4G Use Cases.

every series, music etc (multimedia). is available to them everywhere.

Qs) But why do we need Something beyond 4G
Reason: Mainly to reduce latency & increased relibility

Also :
1. So that good network quality achieved when moving, or in conjusted environments.

2. So, to create a base of VR, 9r augmented reality.

3. Connect everyone & everything

*what changes will 5G bring?
                  ⬇️
             NR (New Radio)

1. significantly high data rates

2. Lower latency (reduction of delay)

3. Uniform experience

4. low cost per bit.

5. performanc will be increased by upto 10x.


* Services offered by 5G

1. EMBB (enhanced mobile broadband)

• improves spectral efficiency Bandwidth & power usage is secondary.

• which appd need it?

1 Peak user data > 10Gbps
2 Network throughout > 1Tbps

Macro cells significatly covers an area of few sq. 
→ Microcells & covers a Small ares

2. mMIC (massive machine type communications)

It an enables all eletric devices, to communicate with the network.
Massive I0T (Internet of things) can scale upto million devices. Also, does offer large coverage conditions

3.  URLLC ( ultre reliable Low latency communications)
necessary for mission critical services.
Empasis on E2E latency.

# Module 3
** 5G networks & its features:

 technologies        Base Stations
  3G                NodeB
  4G                eNodeB
  5G                gNodeB

* Components of next generation core of 5G


1. AMF : Access & Mobility management Manges User equipment access & mobility. function

2. SHF : session management function to supports signaling of IP address allocation & connetivity.

3. User plane function: Handles content generated /consumed by apps etc.

*througput: When Certain amount of data is moved from one place to other in certain amount of time.

How 5G network works. (Network architecture)

Two types of  architecture
1.Stand alone (SA). Only a particular type of momos 

5G Core Network
 ⬇️
5G RAN
 ⬇️
User equipment (UE)

2. Non-standalone (NSA)
   ⬇️            ⬇️
4G radio       5G Radio
Networ         Network
   ⬇️            ⬇️
 4G LTE     5G link carriers
      ⬇️     ⬇️
   Dual Connectivity

In this case the service provideer will slectively deploy limited of 5G stations according to the requirement.

* Techniques that support 5G

1. flexible slot bosed framework
   In simple worde If UE completes the       task faster than expected, then 5G        allocates the left out resources to       some other UE, so it does not get         wasted.

2. Scalable OFDM air interface
(outragonal frequency division multiplexing)

suppose you need to use a wideband channel, but  you don't have the resources. Then OFDM comes into use, it combines many narrowband channel together, so that the the lack of resources do not affect the process.
  ___________
  ___________ wideband channel

  ----------- OFDM combination of                       narrowband channel.

 3. Advanced Channel coding
    (error correction coding)

 It helps to prevent errors like path loss & if the to errors still happen it tries to detoriate its affct, so, that info reaches the the reciever correctly.

 4. Massive MIMO
Device1          Device 2
 T1   _________   R1 }    different
 T2   _________   R2 }     antenas

Both the waves are transmiting to a single device, so the reciever is able to recieve multiple data at the same time. This the is the basic concept. So It improves the data scale.


*One more advantage. MIMO

both Antena's work on the same frequency channel & spectrum. The signals don't interfere with each other bcz MIMO incodes in the transmiters differently. in

To understand simply
If person 1&2 speak in diff languge they will not interfere with the people speaking in different language, even though all 4 of them are sitting in the same room.

5. mmWave (millimeter wave)
wavelength in in mm

* Till now technologies have not been.l able to use the mmwaves efficiently. So, when 5G comes into frame, it will have 1 more advantage that this will solve the availiblity issue because mmWave has abundent spectarum.

Bandwidth range
400MHz-500MHz

*Other networking principles
1. Network Slicing:
   Subset of network component, to           provide E2E every. every slice            contains every element of core            component, the number depends on the      usage amount.

● flexible subscriptions can be made when comes to commercial usage. 

2. software defined networking (SDN) & 
   Network function virtualization (NFV)

 SDN: Hardware is abstracted from the network services & Applications. 
ADVANTAGES:
 1. Rapid Innovation
 2. Centralized Management
 
 NFV: The service provider can rent cloud  servers, So, no need will be there to     buy extra hardware. This will increase    sclability.

 3. MEC (Mobile edge computing)
 shifts resources from far to close to people,  using the services. So, that reduces latency and increases realibility.

# what 4G does not offer?
●It cannot support SDN & NFV, because it cannot use service based architecture, without any hardware.
● Massive MIMO MMWAVE not supported so cannot be used.

# Module 4
3 types of bandwidts under which 5G can function:
1. Low bands < 1GHz (EG: 600MHz, 700MHz it is limited)
2. Mid bands 1GHz- 6GHz (also known as subsix EG: 3.4GHz-4.4GHz etc.)
3. High Bands (utilizes mmWAVE, EG: 24GHz-39GHz)

3 ways of using 5G spectrum:
1. Licensed Spectrum: When a certain person or entity have exclusive rights to operate a band and nobody else can use it. It is very expensive.
2. Unlicensed Spectrum: No need to purchase any spectrum, can be used by anyone. So, higher density will increase interference and slow data speed.
3. Shared Spectrum: First someone has to purchase a spectrum, but can coordinate with different entities to use it by making certain arrangements.

* In mmWAVE the wavelength is in millimeters and also operates in a specific frequency range.

  Qs) What challanges does deployment of mmWAVE offer?
  Ans. 1. It has high frequency so, path loss will be more.
       2. Building penetration loss.

  Qs) What are the advantages of mmWAVE?
  Ans. 1. It has excess to high band width.
       2. Since, the size of antena is inversely propotional to the amount 
          of frequency, more frequency = small antenas. So, we can fit 
          many more mmWAVE antena than usual so more antenas = higher gain.
       3. The antena pannel can coordinate and can focus there energy in 
          the desired direction, so it will increase spectral efficiency.
       4. *** higher path loss can be used as an advantage: 
          Since higher frequency = low coverage area, we can deploy 
          multiple base stations to increase coverage, so network capacity 
          will increase through cell densification.
    
  * mmWAVE deployment opportunities:
    1. Outdoor deployment opportunities: Done with the help of base signa
      Examples: 1. Dence urban deployment: In this case the concept of 
                    cell densification takes place.
                2. Last Mile Solution: this principle states that instead 
                of using hardware wires we use the above stated concept to 
                provide network to a defined area.
    2. Indoor deployment opprtunities: Small cell deployments, so singular 
       connectivity is possible. It is necessary in closed venues, 
       enterprises, underground transport hubs. Since, mmWAVE offers 
       unlimited spectrum it can fulfil all the requirements needed by the 
       above use cases.
       
     Qs) How to provide broad band connectivity in rural areas?
     Ans. Since rural areas are small marco cells are not needed one base 
     station will be enough to provide coverage to an entire chunk of land.
     When the tower needs to connect with main channel, it will treat it 
     as a normal user and communicate with the help of mmWAVE, also known 
     as backhaul.

   * mmWAVE to fixed wireless access
     The main concept is that FWA device will be present in each house it 
     will recieve signals from the base station and will provide internet 
     to the entire house. It will act just like a modem. It is a portable 
     device.

  
# Module 5
*In depth of Massive MIMO (After looking at real life examples we can state that it increases throughput upto 4x)

*Pre-requisites
1. Antena array: pannel of multiple antenas.
   Number of antenas for sub 6: up to 64
   Number of antenas for mmWAVE: up to 512 (if massive MIMO can achive 
   coverage upto this range then it can be easily converted into mmWAVE).

* What is beamforming?
  When all the antenas that are a part of antena array work together in 
  unity then it is known as beamforming. It prevents the wastage of energy 
  caused when all the antenas focus in different directions. It improves 
  signals and thus improves the throughput.

  Benefits of beamforming:
  1. Muliple beams can be formed, depending on implementation. This will 
     implement MU-MIMO (multi-user MIMO). Both beams uses same frequency 
     channel but they need to encoded differently.
  2. If we deploy beams in both horizontal and vertical direction,it will 
     create 3D beam forming.
  3. It offers more coverage area, beause it allows narrow beams to travel 
     further.

     BEAM SWEEPING: It means when a gNodeB is not able to generate 
     multiple beams, it creates a single beam and flashes it in differnt 
     areas at different times. Reapets it on loop.

# Module 6
*5G RAN
BBU(base band unit): The data tha you see on your screens before being converted into freaquency is known as base band.

RRH(remote radio head) or RU(radio Unit): After the base band signal is converted into frequency it is known as Ru/RRH.

*EVOLUTION OF RAN
1. D-RAN (distributed RAN): it means that you need to have a BBU seprately at each base station with RRH for transfer and recieving of data.

2. C-RAN (Centralised RAN): It meqns that you can have a BBU pool(collection of BBU at the same place) so indivisual BBU for RU will not be needed.

*Fronthaul: the wire that carries data from BBU to RRH/RU. 


3. vRAN (virtualised RAN): It functions the same as cRAN but the BBU pool are made on cloud based servers instead of actual hardware. It will create a system that will offer diverse 5G services.
  ADVANTAGES:
  1. Since service providers will not have to purchase hardware there 
     CAPEX & OPEX costs will reduce.
  2. You can buy BBu and RU from different vendors.
  3. It will help in cell densification.

* RAN functional split:
   The BBU can be divided into components:
  1. CU: used for making strategic and long term decisions. So, loacted  
     at a single location. One is present with many number of DU's
  2. DU: This can be located at many locations. Present with mostly 
     every RU.

Qs) what are the advantages of using vRAN
Ans. 1. Cost friendly
     2. Bcz it only has one RU it will help to increase 
       speed and will be more efficient.

* The RAN Protocol Stack
  1.  Use plane control stack
      Supports carrying user data between different 
      applications of UE and gNodeB.
      LAYERS:
      1.PHY (Physical Layer): efficient wireless 
      communication.
      2.MAC: Checks the transmitted messages for 
      errors, does scheduling required to multiplex and 
      demultiplex different channels.
      3.RLC: Segements IT packets and then rearranges 
      them on the recieveing side.
      4.PDCP: Takes care of ciphering and integrity 
      protection of the wireless data transfer. Also, 
      offers duplicacy removal.
      5.SDAP: It maps quality bearer in the right radio 
      bearer according to frequency requirements.

*Difference between SDU and PDU??
 
  3.  Control plane protocol stack
      Supports carrying user data between different 
      applications of UE, gNodeB or core network.
      LAYERS ACCEPT THE ONES MENTIONED IN CONTROL PLANE:
      1.NAS: Assigns IP address to a device
      2.RRC (Radio resource control): Performs most of 
       the functions of SADP. Also, configures system 
       information.

# Everthing about SDAP (SERVICE DATA ADAPTATION PROTOCOL)
  Diverse traffic types offered are: 
  Voice, Broadband, mMTC, URLLC.
  All of the above need different specification that 
  then they to provide there sevice correctly...
  5G follows the principle of QoS (Quality of Service) 
  flows.
  When tranfer of information takes place through PDU 
  session, it contains a radio bearer and a N3 Tunnel.
  Every PDU session has a spectfied Qos Flow, so it is 
  designed according to the the need of data.

   5QI= 5G Qos Identifier.
 
  *Qos Flow Types
  1. GBR (Garaunteed bit rate): In this case the voice 
    is not interupted in the conversation.
      I. Garaunteed flow bit rate (GFBR)
      II. Maximum flow bit rate (MFBR)
      III. Max packet loss rate (MPLR)
  3. Non-GBR flows: Does not garauntee a certain bit 
    rate.
       I.RQI (Reflective Qos): It decided that the 
       device should use the same QFI in the uplink 
       and downlink.
       II. Session-Agreegate maximum bit rate (AMBR)
       III. UE-AMBR
  5. Delay Critical: Used for critally controlled 
   situations, used for remote control devices etc.

*Uplink Qos flows:
 1. Reflective Mapping: When the Qos flows uses the 
 same radio bearer in both uplink and downlink.
 2. Explicit Mapping: When both radio bearer and different in uplink and downlink.
Muliplexing: When the same channel has different PDU session and Qos flows.

# Everything about PDCP (PACKET DATA CONVERGENCE PROTOCOL) Layer:
4 main functions:
1. HEADER cOMPRESSION
    Reduces the length of header by compressing it before transmission and decompresses it before wireless recieving of data.
    It is based on the ROHC (Robust Header Compression)
2. CIPHERING AND INTERGRITY PROTECTION
     Ciphiring is used to prevent eavsdropping , it is done by using an algoritmn NEA. Intergrity protection is done to know the correct source of data origin, done by 
     using an algorithm NIA.
3. ROUTING AND DUPLICATION OF SPLIT BEARESRS
     When the cre network needs to send data to different towers, it uses split bearer which is a type of PDCP. and Duplication can be used to send the exact same data in 
     both the towers.  So it helps in achieving data rates and reliability.
4. IN-SEQUENCE DELIVERY
     It labels the packets so that the delivery of packets is done accordingly.


# Everything about RLC (Radio link control)
 2 main functions:
 1.Segmentation:
    
 2. ARQ- Retransmissions

 RLC MODES:
 1. Transparent modes: NO transmission, No segmentation/reassembly taking place. The channels are designed in such a way.
 2. Unacknowledged mode: SEgmentation, but no retransmission.
 3. Acknowleged mode: Segmentation and retransmission are all supported in this mode.

 # Everything about MAC (Medium Access Control) Layer
  Functions of MAC
  1. Logical-channel multiplexing
  2. hybrid-ARQ retransmissions (follows the stop and wait method: the trinsmitter transmits one block of data and then waits for feedback,
     after the feedback is recieved then another block is sent)
  3. Scheduling
  4. Multiplxing/demultiplexing for Carrier Applications

     *When data is transferred from physical layer to mac layer it is done trough transport channel but when it communicates with RLC layes it is done through logical 
     channels.
*Different types of logical channel
Broadcast Control Channel (BCCH), Paging Control Channel (PCCH), Common Control Channel (CCCH), Dedicated Control Channel (DCCH), Dedicated Traffic Channel (DTCH)

*Different types of transport channel (Transport channels, converts information into blocks before transferring it over)
Broadcast Channel (BCH), Downlink Shared Channel (DL-SCH), Paging Channel (PCH), Uplink Shared Channel (UL-SCH), and Random Access Channel (RACH).

  *MAC layer can also add CE (control Elements) to the transport blocks.
  Some of MAC CE
  1. Scheduling
  2. Random Access
  3. Timing Advance etc.
  # Module 7
  
  * What are private networks: These networks are designed for a 
    particular enterprise, so that they can perform their operations.
    It requires very few base stations, depending upon the area. But, they 
    can also use public networks.

    ADVANTAGES OF CELLULAR PRIVATE NETWORKS:
       1. Design can be based according to customers need.
       2. High degree of reliability and availiblity.
       3. Flexibility of dervices can be controlled.

   *What is Industrial IOT?
    This concept states that all the machines communicate with the same 
    operational server. The server looks into details off all the data 
    recieved, then prepares a concrete summary and sends it two the 
    devices, in order to achieve better performance.

    *Private network for IOT....
     For Example: In a industry their are certian gagets and machines that 
     functions. If the industry has a private network, all the devices 
     will communicate with it. But, suppose if a battery truck that 
     operates there, if it travels than it uses macro level public net or 
     when it is within the premises of factory it uses private net.

    * what factors should be kept in mind while private networks deployment
      1. How much spectrum is needed
      2. Which architecture to use (SA or NSA)
      3. Where should be core network kept (On premise or cloud)
      4. Which RAN to be chosen.

   * Spectrum options for private net & IOT..
     1. Dedicated spectrums: Auctions ar kept so that only industria 
        owners can purchase the spectrum kept aside for IOT.
     2. Licenced spectrum
     3. Unlicenced spectrum
     4. In future syncronised spectrums will come in power, where the 
        network will function according to th availibility of licenced or 
        unlicenced spectrum.


    * What is the difference between WIFI and private network:
    WIFI: It works in the unlicenced spectrum, So when two routers come 
    together it is possible that both of them will interfere with each 
    others signals. Also, it does not offer as much scalibility as private 
    networks.

# Module 8

*Security in 5G
   AIR INTERFACES:
   3GPP Access: When a user tries to access 5G core network over 5G RAN.
   non-3GPP Access: When a user tries to access 5G core network over WIFI, 
   instead of 5G RAN.

  1. Enhanced system design framework: 
     It does not matter which air interface you are using, the core 
     network performs a basic authentication before letting any network in.

     SEAF (Security anchor function): It takes some of the security check 
     load off from the core network and brings it one layer closer to the 
     user, just like in edge computing.

  2.Expanded protection and increased flexibility:
      I. Integrated security credential: If the sim card is not present 
         then also the system's hardware is coded with some security 
         parameters.
      II. Deeper Key hierarchy: It means that the user is always secured 
          from the home network side, whether it is using home network or 
          roming network.
      III. Improved data protection: It will inform the user and device if 
           their data is being tampered with in the control plane or the 
           user plane.

  *IMSI: INTERNATIONAL MOBILE SUBSCRIBER IDENTITY

    *If you are using a sim card you are provided with a subscriber 
    identity. And in order to ensure that the ID is not leaked, certain 
    measures are taken in 5G networks...
       1. Encryption concept is being set up between the user and network 
       before transfering of any important information.
       2. In 5G it can assign temporary ID's from time to time, so leaking 
       of information becomes tough.
       3. When we send a important piece of information, the UE does not 
       send it completely at once, it sends the information in phases, 
       which ensures a multi level authentication, between UE and core 
       network.


# Deployment of 5G
Option 1: EPC to deploy 4G network with eNodeB
Option 2: If a provider does not have legacy 4G netwok then it can only provide with 5G network with gNodeB.

*EN-DC*
Option 3: Dual connectivity, one is known as master RAN  and other is known as secondary RAN.
      I. If people want to get 5G coverage then in this case they use 5G network (secondary RAN) over 4G core.
Option 3a: Data can be send to only eNodeB or gNodeB.
Option 3x: A mixute of Option 3 and 3a.

*NE-DC*
Option 4: 4G access is used as the secondary technology
Option 4a: First data is send to gNodeB then partly sent to eNodeB and device.

Option 5: eLTE
In this case mostly everthing consists of 5G, but the 4G stations are upgraded in order to access 5G.

Option 6: Is the vica versa of option 5, but 5G does not support it.

NG-EN DC
Option 7: This means an enhanced eNodeB can also use 5G thechnology as gNodeB.
