# X570 vs B550 and why you probably shouldn't be buying a X570 motherboard for your Ryzen 5000 processor
  1. [PCIE Gen 4](#pcie-gen-4)
  2. [Price](#price)
  3. [B550 vs X570 Reality](#b550-vs-x570-reality)
  4. [Futureproofing](#futureproofing)
  5. [Conclusion](#conclusion)

# Introduction
A lot of what I am going to say here is very subject to exceptions, so plase read the conclusion for the full list on times when to get a X570 motherboard if I didn't discuss it in the paragraphs specifically. **Credits to WhoopityLongJohn for co-authoring this write-up.**

## PCIE Gen 4
* There has been a lot of buzz around "PCIE Gen 4", an improvement over Gen 3 which improves upon the total bus bandwidth allowing more data to be transferred. The easiest difference to point out between B550 and X570 is that B550 only has a single x16 Gen 4 lane and a x4 for the first M.2 slot whereas all the general lane PCIE and NVME slots are PCIE Gen 4 on X570. However, this is completely irrelevant for most users. In fact, users who are actually using more than one PCIE Gen 4 NVME drive have either a big bank account (generally irresponsible) or more likely to move over to xTR4 because chances are they are doing professional work. 

* Currently, some Gen 4 drives are actually worse than mid/high-tier Gen 3 drives (that are cheaper) in terms of random speeds (are what determine how fast your games load) thereby rendering a consideration of Gen 4 moot for gaming. Oddly enough, some Gen 4 drives that *should* actually be better than current Gen 3 & 4 drives now--not because they are Gen 4, but because they have new controllers like Phison E18 or SM2267/SM2264--have their own issues currently. Even if you are eyeing a good PCIE Gen 4 drive (of which the controllers aren't really optimized themselves nor software on windows currently), the speed difference is less than a single percent (of sub minute load times, basically not noticeable). They are very few people who would benefit from a Gen 4 drive. To the people who say Gen 4 is faster because bigger number better, I raise the example of why no drive is currently saturating the Gen 3 bus bandwidth and thus optimizing in a different way of "NAND"--Intel Optane 905p.

* As for the GPU lanes, not even the 3080 needs PCIE Gen 4. There have been tests to show that PCIE Gen 3 vs Gen 4 on a 3080 is less than 1% different (1% on 4k resolution is nothing much, as where the cards should be used). So Gen 4 is irrelevant currently, and if you're even considering the price point of B550 and X570, futureproofing is not an argument here since SLI is dead and NVME speed differences are pretty small. Secondly, B550 already has PCIE Gen 4 in the top x16 PCIE slot and first M.2 slot--only X570 has more of it. If you need multiple Gen 4 x16 lanes for using NVELINK with multiple-GPUs, you probably should be moving to Threadripper anyways.

## Price
* First of all, the quality of the board (VRM configuration, heatsinks, memory traces) can determine how far you can push your CPU or RAM, but the B550 and X570 chipsets are no different in that regard. B550 is not an inherent downgrade from X570. Rather, it is X570 with features cut out that most people don't need, which also decreases cost. 

* B550--currently--does not have very very expensive motherboards (B550 Unify-X is coming), so if you're dropping $500 on a motherboard, well I guess X570 is for you? The only real reason to get a X570 board is that a B550 board doesn't has something you want/need--which for most people is not an issue.

* If we compare a B550 motherboard and a X570 motherboard at the same price, it is usual assumption that the B550 motherboard will have more features and better cooling solutions. Think of X570 with a premium on top of B550. In this perspective, we see that many of the lower-tier X570 boards are straight-up inferior than cheaper B550 boards (I'm looking at you MSI). We only really see good boards emerge from X570 past the $200 range of which there are still very very top tier B550 boards with more features (MSI X570 Tomahawk lacking some debugging features despite being more than $200 and tailored for overclocking--still a good board though). 

## B550 vs X570 Reality
* B550 vs X570 Extreme4? VRMs are essentially the same, B550 is cheaper, and has a ton of troubleshooting features that the X570 doesn’t have. B550 wins here. 
* B550 vs X570 Aorus Master? VRM is **BETTER** on the B550, you get more rear USBs on B550, and it's cheaper. B550 wins again (yet both boards aren't really worth it. You have to deal with dual BIOS without switches on B550 and X570 is just outclassed at its price bracket)
* You don't need a very expensive motherboard to get the features you want, and you don't need a pesky chipset fan to know it has nice features (a lot of X570 boards have controls for it but not all of them).
* X570 has only two mATX boards, which are both pretty bad compared to B550, which has a ton of good mATX motherboards. Asrock X570m Pro4 is pretty bad--4 by 2 Vcore doubled on 55 amp power stages with the worst heatsink ever. There are B550 boards literally better than it. And the heatsink doesn't have a lot of surface area. Biostar board is 4 by 3 Vcore single, trash rear IO, and never in stock. 

* In the mini-ITX arena, you only have one expansion slot on the motherboard anyways, so why get a more expensive X570 board? Yes, there is a X570i Strix for above $300 and the Crosshair Viii Impact for a lot more, but these boards don't offer much more in terms of features (C8I memory topology is worse than B550i Strix or B550i AX as per Buildzoid). Secondly, the VRMs on the B550 ITX boards is arguably better than their X570 equivalents (X570 just forces airflow through because of fans). Gigabyte B550i AX has 90 amp power stages which is pretty nice for the price.

## Futureproofing
But let's move on to "futureproofing". I could add a ton of reasons why futureproofing is a bad idea conceptually, but here are the examples to disprove that. Zen 3 is the end of AM4 meaning that Zen 4 will be on a new socket type. If you want to upgrade from Zen 1, Zen +, Zen 2, Zen 3, to anything beyond, you will need a new motherboard, processor, and now DDR5 RAM within the next one to two years. So buying a very expensive motherboard now makes no sense in this lense considering you shouldn't be upgrading within a single socket.

## Conclusion
Conclusion is that X570 is not a generation leap over B550 even remotely. It has features most people don't care for and will make you pay extra for: 
- Wanting multiple PCIE Gen 4 SSD's instead of just one 
- Wanting multiple NVME SSDs without losing any SATA ports 
- Wanting to use multiple NVME SSDs, while using an extra PCIE Slot for some form of expansion card. (Not an issue on B550 boards with x8 x8 bifurcation mode lanes)
- Wanting to use chipset as VM passthrough
- USB 3.2 Gen 2 front header (B550 only has Gen 1)
- You want to spend more than $300 on a motherboard
