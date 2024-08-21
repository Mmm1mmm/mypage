<script lang="ts">
  import * as Card from "$lib/components/ui/card";
   import * as Avatar from "$lib/components/ui/avatar";
      let dialog: HTMLDialogElement;
    let value = 0;
    const f = (x: number) => {
        value = x;
        dialog.showModal();
    }
</script>
<div class="p-4 pt-9 "><!-- divで囲う --->
    <Card.Root class="w-60 h-[29.75rem]">
        <Avatar.Root class="w-[75px] h-[75px] relative -top-7 left-[5.125rem]"> <!-- relative(相対的に動かす) -->
            <Avatar.Fallback>高専 太郎</Avatar.Fallback>
            <Avatar.Image src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.ubSQVjUQ0MATRedUJvku6AHaHa%26pid%3DApi&f=1&ipt=f27a3eb1d4b56626a4f6456235b5e2c2c06718fff76a42f959a200513c624802&ipo=images" alt="@null" />
        </Avatar.Root>
        <Card.Header class="-mt-5"> <!-- 違和感のある空白をなくす(上に動かす) -->
            <Card.Title class="relative left-[3.75rem]">高専 太郎</Card.Title>
            <Card.Description class="relative left-[3rem]">2024/8/19 14:20</Card.Description>
        </Card.Header>
         <Card.Content class="m-[1.15rem] relative -top-6 left-5">
         <dialog bind:this={dialog}>
    <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.R49lKa86NMhl7mlK_nwF1wHaMi%26pid%3DApi&f=1&ipt=bf28d38e31823fc2e3225afdb7a8fc8985b1c8d0c99494a597a22c988efabcf7&ipo=images" alt="yaai" class="w-[9.5rem] h-[15.5rem] relative left-[3rem] top-[2rem]" />
    <button variant="destructive" on:click={() => dialog.close()}><p1 class="relative left-[5rem] top-[4rem]">閉じる</p1></button>
    <Card.Root class="w-[15rem] h-[5rem]">
    </Card.Root>
</dialog>
<button class="p-8" variant="secondary" on:click={() => f(1024)}>
<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.R49lKa86NMhl7mlK_nwF1wHaMi%26pid%3DApi&f=1&ipt=bf28d38e31823fc2e3225afdb7a8fc8985b1c8d0c99494a597a22c988efabcf7&ipo=images" alt="hana" class="relative -left-[1rem] ">
</button>
        </Card.Content>
        <Card.Footer>
        <Card.Description class="relative -top-5 left-[3rem]">高専 太郎さんから
        <Card.Description class="relative top-1 ">花が届きました!</Card.Description>
        </Card.Description>
        
        </Card.Footer>
    </Card.Root>
        <Card.Root class="w-60 relative left-[18rem] -top-[29.77rem]">
        <Avatar.Root class="w-[75px] h-[75px] relative -top-7 left-[5.125rem]"> <!-- relative(相対的に動かす) -->
            <Avatar.Fallback>高専 花子</Avatar.Fallback>
            <Avatar.Image src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.ubSQVjUQ0MATRedUJvku6AHaHa%26pid%3DApi&f=1&ipt=f27a3eb1d4b56626a4f6456235b5e2c2c06718fff76a42f959a200513c624802&ipo=images" alt="@null" />
        </Avatar.Root>
        <Card.Header class="-mt-5"> <!-- 違和感のある空白をなくす(上に動かす) -->
            <Card.Title class="relative left-[3.75rem]">高専 花子</Card.Title>
            <Card.Description class="relative left-[3rem]">2024/8/19 14:25</Card.Description>
        </Card.Header>
        <Card.Content class="m-10">
            <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.CuO36D4LjelipPmwicFqTAHaKe%26pid%3DApi&f=1&ipt=4b37ee0c1816c941cf715be34e3742e3fea58fed5f90655bd95c13b9b7f986a3&ipo=images" alt="shadcn"/>
        </Card.Content>
        <Card.Footer>
        <Card.Description class="relative -top-5 left-[2.5rem]">高専 花子さんから
        <Card.Description class="relative top-1 ">花が届きました!</Card.Description>
        </Card.Description>
        
        </Card.Footer>
    </Card.Root>
        <Card.Root class="w-60 relative left-[36rem] -top-[59.48rem]">
        <Avatar.Root class="w-[75px] h-[75px] relative -top-7 left-[5.125rem]"> <!-- relative(相対的に動かす) -->
            <Avatar.Fallback>高専 直美</Avatar.Fallback>
            <Avatar.Image src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.ubSQVjUQ0MATRedUJvku6AHaHa%26pid%3DApi&f=1&ipt=f27a3eb1d4b56626a4f6456235b5e2c2c06718fff76a42f959a200513c624802&ipo=images" alt="@null" />
        </Avatar.Root>
        <Card.Header class="-mt-5"> <!-- 違和感のある空白をなくす(上に動かす) -->
            <Card.Title class="relative left-[3.75rem]">高専 直美</Card.Title>
            <Card.Description class="relative left-[3rem]">2024/8/19 14:30</Card.Description>
        </Card.Header>
        <Card.Content class="m-10 mt-6">
             <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.7Gb_b2K9MnTwwm4rZtZxVwHaLo%26pid%3DApi&f=1&ipt=b03dfd7f40ffb0477662c20613f3c466cc55ab5a1026ec2950cc41f7189a0798&ipo=images" alt="shadcn" />
        </Card.Content>
        <Card.Footer>
        <Card.Description class="relative -top-5 left-[3rem]">高専 直美さんから
        <Card.Description class="relative top-1 ">花が届きました!</Card.Description>
        </Card.Description>
        
        </Card.Footer>
    </Card.Root>
    <style>
    p1{
        font-size: 2rem
    }
    p{
        font-size: 10rem;
    }
    </style>
    
</div>