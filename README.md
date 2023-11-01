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
     2. Bcz it only has one RU it will help to increase speen and will 
      be more efficient.

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










